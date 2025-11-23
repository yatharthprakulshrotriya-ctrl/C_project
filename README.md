# C_project
Shop_Inventory
# 🏪 Shop Inventory Management System (C)

A dynamic **console-based inventory management system** written in C, designed for managing items categorized under various sections. It supports item addition, selling, saving inventory to a file, and loading previously stored data.

---

## Features

1. Create inventory with:
  (i) Shopkeeper information like Name, age, address,etc.
  (ii) Categories like Food, Beverages, Notebooks,etc. using dynamic memory allocation ('malloc`, `realloc`)
  (iii) Items within each category like inside Food we have Chips storing them in a linked list.
- Add new categories or items using malloc
- Sell an item and update quantity
- Display inventory and it only prints different categories
- Save inventory to 'inventory.txt`
- Load saved inventory back into memory

____________________________________________________________________________________________

## Data Structures Overview

'struct shopkeeper' - Holds shop owner details and all category data
'struct category_node` - Represents a category containing multiple items
'struct item_nod' - Represents individual items stored as a linked list

____________________________________________________________________________________________

### Program Architecture

