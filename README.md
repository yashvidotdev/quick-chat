# ✨ Quick Chat ✨

Quick Chat is a real-time chat application built using the MERN stack, enhanced with Socket.io for real-time messaging, and styled with TailwindCSS and Daisy UI. This application includes features like authentication and authorization, online user status, and global state management.

## Features

- 🌟 **Tech stack**: MERN + Socket.io + TailwindCSS + Daisy UI
- 🎃 **Authentication & Authorization**: Secure your application with JWT.
- 👾 **Real-time messaging**: Implemented using Socket.io for seamless communication.
- 🚀 **Online user status**: See who's online in real-time.
- 👌 **Global state management**: Managed with Zustand for efficient state handling.
- 🐞 **Error handling**: Comprehensive error management on both server and client sides.
- ⭐ **Deployment**: Deploy your application like a pro for FREE!
- ⏳ **And much more!**

## Prerequisites

Ensure you have Node.js and npm installed on your machine. You can download them from [nodejs.org](https://nodejs.org/).

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yashvidotdev/quick-chat.git
```
2. Navigate to the project directory:

```bash
cd quickchat
```

### Setup Backend

1. Navigate to the backend folder:

```bash
cd backend
```

2. Install dependencies:

```bash
npm install
```
3. Create a `.env` file in the `backend` folder and include the following variables:

```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

4. Start the backend server:

```bash
npm run dev
```

### Setup Frontend

1. Navigate to the frontend folder:

```bash
cd frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend server:

```bash
npm run dev
```
## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.
