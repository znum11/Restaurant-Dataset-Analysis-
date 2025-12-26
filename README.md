# Restaurant-Dataset-Analysis-
The objective of this analysis is to analyse Restaurant Orders using SQL. 
Restaurant Dataset Analysis using SQL
Objective:
The objective of this dataset is to analyse Restaurant Orders using SQL. It facilitates customer ordering behaviour analysis, menu item performance tracking, and revenue generation insights by organising and querying order details and menu item data.
The dataset supports data cleaning, aggregation, and sales analysis, making it useful for understanding customer preferences, optimising menu offerings, and improving overall restaurant operations.
Database Design
•	Name of Database: restaurant_db
•	Table Created I: order_details
o	Columns: order_details_id, order_id, order_date, order_time, item_id
•	Table Created II: menu_items
o	Columns: menu_item_id, item_name, category, price


SQL Queries Implemented
•	Table Creation:
Defined primary keys for both tables (order_details_id and menu_item_id) to ensure unique identification of each record.
•	Data Insertion:
Populated the order_details and menu_items tables with real-world restaurant ordering data.
•	Data Retrieval:
Used SELECT queries to fetch records, calculate the most and least ordered items, analyse sales by category, and determine peak ordering times.
•	Joins & Relationships:
Connected order_details and menu_items using a foreign key relationship through item_id and menu_item_id to enable meaningful analysis of orders and menu items.

Implementation and Testing
•	Imported and structured the database schema based on restaurant order data.
•	Performed data cleaning by removing records with NULL item_id to ensure accuracy.
•	Ensured smooth join operations between order_details and menu_items.
•	Tested query performance by retrieving top-selling items, analysing revenue patterns, and evaluating ordering trends by time and category.
Final Outcome
•	The Restaurant Orders database successfully manages essential restaurant operation data, including detailed order records and comprehensive menu item information.
The structured SQL database improves data accessibility, ensures accurate sales analysis, and supports strategic decision-making for menu optimisation and business growth.
The implementation enhances the restaurant’s ability to track customer preferences, maximise revenue opportunities, and plan future menu and marketing strategies.


Findings/Key Insights:-  The most ordered Items from the menu were Hamburgers, and the least ordered items were Chicken Tacos.
The Asian category sold the highest number of items, while the American category sold the least.
Thus, the restaurant should focus on expanding the Asian menu offerings to leverage its popularity, while revisiting the American menu to improve its performance or update it based on customer preferences. The busiest Hour of the day was around 12 PM, and the least no. of orders were received at 5 AM. So it would be recommended to have some extra staff around the 12th hour to make the operations run more smoothly.
