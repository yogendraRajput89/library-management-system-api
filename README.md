* Library Management System

This is a simple **Java console-based Library Management System** that allows users to:

- Add new books
- View all books
- Issue a book
- Return a book

It uses core Java concepts like:
- Classes & Objects
- Constructors
- HashMap for storing data
- Scanner for user input
- Loops and conditionals


* Classes

- **Book**: Represents a book with ID, title, author, and issue status.
- **User**: Represents a library user (not actively used for login in this version).
- **Library**: Contains the main logic for book operations.
- **LibraryManagementSystem**: The main class that runs the menu-driven program.

---

* Features

* Add Book
User is prompted to enter book title and author. Each book is auto-assigned a unique ID.

* View Books
Displays the list of all books with their details including whether they are issued or not.

* Issue Book
Allows issuing a book by entering its ID, only if it's not already issued.

* Return Book
Allows returning a book by ID, only if it's currently issued.

* Exit
Ends the program.

---

* How to Run

1. **Save** the code in a file named `LibraryManagementSystem.java`.
2. **Compile** it:
   ```bash
   javac LibraryManagementSystem.java
