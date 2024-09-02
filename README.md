# MERN Stack School Management System


I developed this School Management System using the MERN stack (MongoDB, Express.js, React, Node.js), drawing inspiration from the original project created by @Yatunyi15075. The frontend is built with React and Vite, incorporating styled-components for a sleek and modern design.

## Key Features:

- **Admin Dashboard:** Manage student records, teacher information, courses, exams, assignments, track student attendance, add teachers, and view school performance metrics.
- **Student Dashboard:** View class schedules, manage assignments, submit work, and track academic progress.
- **Teacher Dashboard:** Oversee class schedules, assign and grade exams and assignments, and monitor student performance.

## Core Operations:

- **Student Management:** Add and manage student records, including personal and academic details.
- **Class Management:** Create and manage classes, assign teachers, and schedule sessions.
- **Exam Management:** Develop and manage exams, assign them to classes, and grade submissions.
- **Assignment Management:** Create and manage assignments, track student submissions.
- **Teacher Management:** Add and manage teacher profiles.
- **Performance Metrics:** Access various metrics to assess and improve school performance.

## Technologies Used:

- **Frontend:** React, Vite, styled-components
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Deployment:** Not deployed yet

## Setup Instructions:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mern-school-management-system.git
   ```

2. **Install dependencies:**

   ```bash
   cd mern-school-management-system
   npm install
   ```

3. **Set up environment variables:**

   - Create a `.env` file in the root directory.
   - Define the following variables:

     ```
     PORT=4000
     MONGODB_URI=your_mongodb_connection_string
     SECRET_KEY=your_secret_key_for_jwt
     ```

4. **Run the development servers:**

   - Start the frontend server:

     ```bash
     npm run dev
     ```

   - Start the backend server:

     ```bash
     npm start
     ```

5. **Access the application:**

   Navigate to `http://localhost:5173` for the frontend and `http://localhost:4000` for the backend.

## Contributing

I welcome contributions! Feel free to submit pull requests, report bugs, or suggest features to enhance this project.

## License

This project is licensed under the [MIT License](LICENSE).
