# Medical Document Manager - HealthVault 🏥
A complete full-stack medical document management system built with MongoDB, Express, Node.js, and Vanilla JavaScript

---

## 📋 Project Description
Medical Document Manager is a full-stack healthcare management web application developed to help users securely store, organize, and manage medical information digitally in one centralized platform. The system is designed to simplify healthcare record management and provide easy access to important medical data anytime and anywhere.

---

## ✨ Features & Functionalities

### 1. **User Authentication** 🔐
- Secure user registration and login
- JWT-based authentication
- Password hashing with bcryptjs
- Token-based session management
- Auto-logout on token expiry

### 2. **Medical Document Management** 📄
- Upload medical documents (PDF, JPG, PNG)
- Organize documents by type and date
- Document metadata tracking
- Secure file storage as base64
- View, download, and delete documents

### 3. **Appointment Scheduling** 📅
- Schedule doctor appointments
- Choose in-person or virtual mode
- Automatic email confirmations
- View upcoming appointments
- Cancel appointments with notifications
- Appointment reminders

### 4. **Health Metrics Recording** ❤️
- Record blood pressure
- Track heart rate
- Monitor weight
- Record blood glucose
- Track temperature
- View historical health data
- Trend analysis

### 5. **Doctor Directory** 👨‍⚕️
- Save favorite doctors
- Store doctor contact information
- Hospital and specialty information
- Quick access to healthcare providers
- Manage multiple doctors

### 6. **Activity Logging** 📊
- Track all user actions
- Timestamp every operation
- View activity history
- Audit trail for security

### 7. **Responsive Design** 📱
- Mobile-friendly interface
- Tablet optimized
- Desktop experience
- Touch-friendly controls
- Adaptive layouts

### 8. **Professional UI/UX** 🎨
- Modern healthcare theme
- Intuitive navigation
- Smooth animations
- Dark sidebar design
- Professional color scheme

---

## 🛠️ Technology Stack

### Frontend
```
- HTML5 (Semantic markup)
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+, No frameworks)
- Responsive Design (Mobile-first approach)
```

### Backend
```
- Node.js (Runtime)
- Express.js (Web framework)
- MongoDB (Database)
- Mongoose (ODM)
- JWT (Authentication)
- bcryptjs (Password hashing)
- Nodemailer (Email service)
- CORS (Cross-origin requests)
```

### Database
```
- MongoDB Atlas (Cloud database)
- MongoDB Compass (Visual tool)
```

### Tools & Services
```
- Git & GitHub (Version control)
- Postman (API testing)
- VS Code (IDE)
- MongoDB Atlas (Cloud DB)
- MongoDB Compass (DB visualization)
```

---

## 📁 Project Structure

```
medical-doc-manager/
│
├── backend/
│   ├── server.js          # Express server & API endpoints
│   ├── models.js          # MongoDB schemas with Mongoose
│   ├── .env              # Environment variables
│   ├── .env.example      # Example env file
│   ├── package.json      # Dependencies
│   ├── package-lock.json # Locked versions
│   └── README.md         # Backend documentation
│
├── frontend/
│   ├── public/
│   │   └── index.html              # Main HTML file
│   ├── src/
│   │   ├── index.js               # Main app logic
│   │   ├── api.js                 # API utility functions
│   │   └── utils.js               # Helper functions
│   ├── styles/
│   │   ├── main.css              # Global styles
│   │   ├── auth.css              # Auth page styles
│   │   ├── dashboard.css         # Dashboard styles
│   │   ├── components.css        # Component styles
│   │   └── responsive.css        # Responsive design
│   ├── assets/
│   │   ├── images/               # Image assets
│   │   └── icons/                # Icon assets
│   ├── package.json              # Dependencies
│   ├── .env                      # Environment variables
│   ├── .gitignore               # Git ignore
│   └── README.md                 # Frontend documentation
|────

```

---

## 🚀 Installation & Setup

### Prerequisites
```bash
Node.js >= 14.0.0
MongoDB Atlas Account
Git
Python 3.6+ (for frontend server)
```

### Backend Setup

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/medical-doc-manager.git
cd medical-doc-manager/backend
```

2. **Install dependencies**
```bash
npm install
```

3. **Setup environment variables**
```bash
cp .env.example .env
```

4. **Update .env file** with your MongoDB URI:
```
PORT=5000
MONGODB_URI=mongodb+srv://username:password@cluster0.xxxxx.mongodb.net/medical_db?retryWrites=true&w=majority
JWT_SECRET=medical-doc-manager-secret-2026
JWT_EXPIRE=30d
EMAIL_USER=your-email@gmail.com
EMAIL_PASSWORD=your-app-specific-password
FRONTEND_URL=http://localhost:3000
```

5. **Start backend server**
```bash
npm start
```

Expected output:
```
✅ MongoDB Connected Successfully!
📊 Database: medical_db
✅ Server running on http://localhost:5000
🏥 MedDocs Pro - MongoDB Edition Started
```

### Frontend Setup

1. **Navigate to frontend folder**
```bash
cd ../frontend
```

2. **Update API URL** in `src/api.js` if needed:
```javascript
const API_BASE_URL = 'http://localhost:5000/api';
```

3. **Start frontend server**
```bash
npm start
# or
python -m http.server 3000
```

4. **Open in browser**
```
http://localhost:3000
```

---

## 📱 How to Use

### 1. Authentication
1. Go to http://localhost:3000
2. Click "Sign Up" to create account
3. Fill in details (First Name, Last Name, Email, Password)
4. Click "Create Account"
5. Login with credentials

### 2. Upload Documents
1. Click "📄 Documents" in sidebar
2. Click "+ Upload" button
3. Fill document details (Title, Type, Date, Provider)
4. Select PDF/Image file
5. Click "Upload"
6. Document appears in list

### 3. Schedule Appointments
1. Click "📅 Appointments" in sidebar
2. Click "+ Schedule" button
3. Fill appointment details
4. Email confirmation sent to registered email
5. View in appointments list

### 4. Manage Doctors
1. Click "👨‍⚕️ Doctors"
2. Click "+ Add Doctor"
3. Enter doctor information
4. Save to directory
5. Quick access when scheduling

### 5. Health Alerts
1. Click "🚨 Alerts"
2. Click "+ Create Alert"
3. Set alert type and priority
4. Add description
5. Get reminders

---

## 👥 Team Members
- Yashasvi Panchal - EN23CS3011158
- Yashika Mehta - EN23CS3011159
- Yashwini Shinde - EN23CS3011164 
---

## Screenshots
<img width="1897" height="1017" alt="1" src="https://github.com/user-attachments/assets/69796394-949e-46bb-ad99-78f1f3e194a2" />
<img width="1919" height="1005" alt="2" src="https://github.com/user-attachments/assets/f4349318-b33a-4295-8f3e-9e4d84621c92" />
<img width="1563" height="824" alt="3" src="https://github.com/user-attachments/assets/22cddb70-b955-453a-9676-874245ed0818" />
<img width="1895" height="675" alt="4" src="https://github.com/user-attachments/assets/b813d49d-d4d7-44b6-8dee-104ffcdf4256" />
<img width="316" height="379" alt="5" src="https://github.com/user-attachments/assets/ed007e34-19ce-493e-9a75-2c63f68848ea" />
<img width="504" height="228" alt="6" src="https://github.com/user-attachments/assets/088b946f-ec16-4771-9ed1-c9afa493047f" />



