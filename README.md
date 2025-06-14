# 📬 Chat App

A modern full-stack real-time chat application where users can send text messages, files, and photos to their friends. Built using **React**, **MongoDB**, **Google Drive**, and deployed with **Render**, this app is designed for public use and delivers a sleek, user-friendly messaging experience.

🌐 **Live Demo:** [https://chat-app-rnp5.onrender.com](https://chat-app-rnp5.onrender.com)

---

## 🖼️ Features

- 💬 Real-time 1-on-1 messaging
- 📁 File and image sharing via Google Drive integration
- 🔒 User authentication
- 🧑‍🤝‍🧑 Friend list management
- 🌙 Clean and intuitive user interface
- 📱 Responsive design for mobile and desktop

---

## 🛠️ Tech Stack

### Frontend
- **React** with functional components and hooks
- **Axios** for API requests
- **Tailwind CSS** or custom CSS for styling (based on screenshots)

### Backend
- **Node.js + Express**
- **MongoDB** for storing user and message data
- **Mongoose** for schema modeling

### File Handling
- **Google Drive API** to upload and store files securely
- Shared links used for file access

### Deployment
- **Render** for frontend and backend hosting

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/chat-app.git
cd chat-app
```

### 2. Install Dependencies
Install frontend and backend dependencies:

```bash
cd client
npm install

cd ../server
npm install
```

### 3. Set Up Environment Variables
Create `.env` files in both `/client` and `/server` with the appropriate values:

#### `.env` (Backend)
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GOOGLE_DRIVE_FOLDER_ID=your_shared_drive_folder_id
JWT_SECRET=your_jwt_secret
```
#### `.env` (Frontend)
```env
REACT_APP_API_URL=http://localhost:5000
```
### 4. Run Locally
Start the development servers:

```bash
# In /server
npm run dev

# In /client
npm start
```

## Security Notes
- Files are stored on Google Drive using a shared folder with permission-controlled access.

- JWT-based authentication for user sessions.

## Contributing
Contributions are welcome! Open an issue or submit a pull request with improvements or bug fixes.

## License
MIT License — feel free to use and modify this project.





