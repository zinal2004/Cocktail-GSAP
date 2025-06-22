# 🍸 Cocktail Landing Page

A smooth and animated cocktail-themed landing page built with **React + Vite + GSAP**.  
This project uses **GreenSock animations (GSAP)** for an engaging scroll experience and is fully responsive for all devices.

---

## 🚀 Features

- 🎨 Sleek UI and color-themed design
- 💫 Smooth scroll and entry animations (GSAP)
- 📱 Fully responsive (mobile-first)
- 🎥 Scroll-controlled background video
- ✨ Split text reveal animations
- ⚡️ Fast Vite build and performance-optimized

---

## 🛠️ Tech Stack

- **React.js** (via Vite)
- **GSAP** (with ScrollTrigger and SplitText)
- **Tailwind CSS** (custom CSS)
- **FFmpeg** (for optimizing video)
- **Responsive Hooks** (via `react-responsive`)

---

## 📸 Live Demo

👉 [View Live Site](https://mixologybyz.vercel.app/)

---

## 📦 Installation & Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/cocktail-gsap.git
   cd cocktail-gsap
2. **Install dependencies**

```bash
npm install
```
3. **Start development server**

```bash
npm run dev
Visit http://localhost:5173
```

4. **Optimizing Your Video (Optional but Recommended)**
   **Use FFmpeg:**
```bash
ffmpeg -i input.mp4 -vf scale=960:-1 -movflags faststart -vcodec libx264 -crf 20 -g 1 -pix_fmt yuv420p output.mp4
```
