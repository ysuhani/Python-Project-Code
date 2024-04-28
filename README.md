# Interactive Food Ordering System

The objective of this project is to develop an interactive food ordering system using Python, empowering users to effortlessly navigate through a menu, select items, place orders, and make payments. By leveraging Python's tkinter library for GUI development and integrating additional functionalities such as generating PDF reports for placed orders, this system aims to streamline the food ordering process, providing both customers and restaurant staff with a seamless and efficient experience.

It was a fun project, which helped me to understand how we can order food online using just a code.

Implementation Plan:
- Python Packages/Modules:
•	`tkinter`: Utilized for constructing the graphical user interface (GUI).
•	`messagebox` from `tkinter`: Employed for displaying messages and alerts to users.
•	`reportlab`: Utilized for generating PDF reports of placed orders.
•	reportlab.lib.pagesizes Specifies the page size for the PDF document as a standard letter size.

Dataflow/Major Functionalities:
1. Users are presented with a graphical menu interface displayed on the GUI.
2. They can browse through menu items and select desired ones by clicking on them.
3. Selected items are added to the order list, with the total amount dynamically updated.
4. Upon completing the selection, users proceed to checkout, where they choose a payment method (cash, credit card, or online payment). Also users are prompted to enter their name and address to identify the customer & to facilitate the delivery.
5. After selecting a payment method, a confirmation message is displayed, signifying the order's confirmation.
6. A "Thank You" message acknowledges the completion of the order process.
7. Additionally, a PDF report containing the placed orders and the total amount  paid is saved for record-keeping.
UIs/Databases:
- The user interface (UI) comprises a main window housing labels, listboxes, buttons, and message boxes to exhibit the menu, order details, and payment options.
- No databases are incorporated into this project, maintaining its simplicity as a standalone ordering system.



Input/Output:
- Input: Users interact with the GUI to select menu items and payment options.
- Output: Upon confirmation, the GUI displays a confirmation message, affirming the successful placement of the order.

Benefits:
- Facilitates a user-friendly, simple and easy to understand,efficient food ordering process for all groups of customers.
- Reduces manual order-taking and processing efforts for restaurant staff.
- In this ordering system, a unique feature is that upon completing an order, a PDF containing the total order value, selected payment method, customer name, and customer address is automatically saved in the customer's system. This makes it easier to keep track of order items without having to search through emails and apps.
  
Conclusion:
The interactive food ordering system developed in Python caters to the evolving demands of the food service industry by offering a digital solution that enhances order management and customer satisfaction. By leveraging Python's versatility and integrating additional functionalities such as PDF report generation, this project demonstrates a commitment to providing innovative solutions that streamline operations and elevate the customer experience in the food service sector.
