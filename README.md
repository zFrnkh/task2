# Summer Task - Web Form with PHP & MySQL

## ✅ Task Description

This project is part of the summer internship tasks.  
It is a simple PHP-based web application that allows the user to:

- Add new users by name and age.
- Store the data in a MySQL database.
- Display all records in a table.
- Toggle the status (0 or 1) for each record using a button.

---

## 🧱 Technologies Used

- HTML
- CSS (basic styling if needed)
- PHP
- MySQL
- phpMyAdmin (for database management)
- XAMPP (local server environment)

---

## 🧪 How to Run the Project

1. Make sure XAMPP is installed.
2. Place the project folder (`summer_task`) inside:  
   `C:\xampp\htdocs\`
3. Start Apache and MySQL from the XAMPP control panel.
4. Open your browser and go to:  
   `http://localhost/phpmyadmin`
5. Create a database named: `training`
6. Run the following SQL code to create the table:

```sql
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(50),
  age INT,
  status TINYINT DEFAULT 0
);
