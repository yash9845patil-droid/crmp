How to run the SmartConnect CRM  Project
1. Download the  zip file

2. Extract the file and copy crm folder

3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)

4. Open PHPMyAdmin (http://localhost/phpmyadmin)

5. Create a database with name crm

6. Import crm.sql file(given inside the zip package in SQL file folder)

7.Run the script http://localhost/crm (frontend)

8.Run the script http://localhost/crm/admin 

Credential for admin panel :

Username: admin
Password: admin

Credential for user panel :

Username: user@gmail.com
Password: 9876543210


Project Summary 
The CRM Ticketing System is a web-based platform designed to help small and medium-sized businesses (SMBs) efficiently manage customer service requests. Built with PHP and MySQL as the core technologies, this system provides a simple yet effective way for businesses to keep track of their customer interactions and resolve issues promptly.

User Experience and Core Functionalities
The application allows customers to register, log in, and submit support tickets through a clean, user-friendly interface. Upon logging in, users are directed to their dashboard, where they can create new support tickets or view existing ones. The system offers functionality for updating ticket statuses and adding further communication, making it easier to manage ongoing support requests.

The ticket creation process is straightforward, where users fill in details about their issues, and the system submits this information into the database. Support staff, via the admin dashboard, can review incoming tickets, respond to customer inquiries, and update the status of these tickets, ensuring clear communication between the customer and the support team.

Admin Panel for Managing Tickets
The system also includes an admin section, which enables administrators to monitor and respond to tickets. The admin dashboard provides an overview of submitted tickets, allowing admins to view the status of each ticket, assign priority, and respond to customer inquiries. This module enhances efficiency by offering tools to manage multiple customer service requests at once, streamlining the entire support process.

Profile and User Management
The platform includes user profile management features, allowing users to update their personal information and passwords as needed. The forgot-password functionality ensures that users can easily recover access to their accounts, further improving the system’s usability.

Session and Authentication Management
User sessions are handled through PHP’s built-in session management capabilities, ensuring secure access to user-specific data. The application also provides a logout feature, which securely ends the session, further enhancing security.

Frontend and Design
On the frontend, the application leverages HTML, CSS, and SCSS for layout and design, with jQuery handling interactive elements such as real-time feedback and form validation. The design focuses on simplicity and usability, ensuring that both customers and admins can navigate the system with ease. The layout is responsive, making it accessible across different devices, from desktop to mobile.

JavaScript Integration
To enhance user interactivity, the application uses jQuery for handling various client-side functionalities, such as submitting forms asynchronously, updating ticket statuses in real time, and managing timers for session expirations. These dynamic behaviors help to create a more engaging and responsive user experience.

Security and Data Handling
The platform emphasizes security in user authentication and data handling. Login credentials are validated through secure PHP sessions, and user data is stored securely in a MySQL database. Additionally, features like change password and forgot password add layers of security, ensuring that users can safely manage their accounts.

Conclusion
The CRM Ticketing System is an efficient and scalable solution designed to meet the needs of businesses looking to streamline their customer service process. By focusing on ease of use, real-time ticket management, and a clean, responsive design, the system enables businesses to better manage their customer interactions, ultimately improving customer satisfaction and support efficiency. The modular design of the system makes it easy to customize and expand based on future needs, offering businesses a flexible platform to grow their operations.