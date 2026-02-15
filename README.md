# MavenMarketReport_PowerBI (Work In Progress)

## Project Overview
This project is part of Maven Analytics course "MS Power BI Desktop for Business Intelligence". The purpose of the project is to practice Power BI skills while working with data from Maven Market, a multi-national grocery chain. The goal was to work through the full BI workflow — from raw CSV files to a fully interactive dashboard — using industry‑standard techniques. This project simulates a real-world retail analytics scenario, focusing on transforming raw operational data into insights for decision‑making.

Screenshots of the project are found in the Images-folder of this repo. 

## What I Learned
- How to clean, transform, and model data using Power Query
- How to design a proper star schema and manage relationships
... 

## Summary
###Part 1: Data Preparation
- Connected all Maven Market CSV files into Power BI
- Cleaned and transformed data (data types, formatting, null handling)
- Created new calculated columns (full names, birth year, discount price, address fields, date intelligence, etc.)
- Combined 1997–1998 transaction files using folder import
- Disabled refresh for lookup tables and applied all transformations

###Part 2: Data Modeling
- Built a star schema with lookup tables (Customers, Products, Stores, Regions, Calendar) above fact tables (Transactions, Returns)
- Created one‑to‑many, single‑direction relationships
- Added inactive relationship for stock date
- Hid foreign keys and unnecessary fields from Report View
- Formatted dates, currency fields, and geographic fields
- Saved the structured data model

### Part 3: DAX Calculations (On going)
- Added calculated columns (Weekend flag, End of Month, Price Tier, Current Age, Priority, Years Since Remodel, etc.)
- Created core measures:
- Quantity Sold / Returned
- Total Transactions / Returns
- Return Rate
- Weekend Transactions & % Weekend
... 

### Part 4: Building the Report (Not started yet)
... 

## Tools used
Power BI
- Power Query
- Data Modelling
- DAX
- Data Visualization
CSV
