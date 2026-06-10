<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 240" width="100%">
  <defs>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1a2332" stroke-width="0.8"/>
    </pattern>
    <linearGradient id="fadeL" x1="0" x2="1" y1="0" y2="0">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="30%" stop-color="transparent"/>
    </linearGradient>
    <linearGradient id="fadeR" x1="0" x2="1" y1="0" y2="0">
      <stop offset="70%" stop-color="transparent"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <linearGradient id="fadeT" x1="0" x2="0" y1="0" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="40%" stop-color="transparent"/>
    </linearGradient>
    <linearGradient id="fadeB" x1="0" x2="0" y1="0" y2="1">
      <stop offset="55%" stop-color="transparent"/>
      <stop offset="100%" stop-color="#0d1117"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="860" height="240" fill="#0d1117"/>
  <rect width="860" height="240" fill="url(#grid)"/>
  <rect width="860" height="240" fill="url(#fadeL)"/>
  <rect width="860" height="240" fill="url(#fadeR)"/>
  <rect width="860" height="240" fill="url(#fadeT)"/>
  <rect width="860" height="240" fill="url(#fadeB)"/>

  <circle cx="430" cy="118" r="180" fill="none" stroke="#00ff9c" stroke-width="0.4" opacity="0.15"/>
  <circle cx="430" cy="118" r="220" fill="none" stroke="#00ff9c" stroke-width="0.3" opacity="0.08"/>

  <!-- Shell prompt -->
  <text x="430" y="52" font-family="monospace" font-size="12" fill="#00ff9c" opacity="0.5" text-anchor="middle">
    &gt; initializing profile.sh
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="2.4s" repeatCount="indefinite"/>
  </text>

  <!-- Main name -->
  <text x="430" y="108" font-family="'Courier New', monospace" font-size="42" font-weight="bold" fill="#ffffff" text-anchor="middle" letter-spacing="3" filter="url(#glow)">
    YASHRAJ AGAWANE
    <animate attributeName="opacity" values="0;1" dur="0.6s" fill="freeze"/>
  </text>

  <!-- Left divider -->
  <line x1="200" y1="120" x2="310" y2="120" stroke="#00ff9c" stroke-width="0.8" opacity="0.4">
    <animate attributeName="x1" values="430;200" dur="0.9s" fill="freeze" begin="0.6s"/>
    <animate attributeName="opacity" values="0;0.4" dur="0.2s" fill="freeze" begin="0.6s"/>
  </line>

  <!-- Right divider -->
  <line x1="550" y1="120" x2="660" y2="120" stroke="#00ff9c" stroke-width="0.8" opacity="0.4">
    <animate attributeName="x2" values="430;660" dur="0.9s" fill="freeze" begin="0.6s"/>
    <animate attributeName="opacity" values="0;0.4" dur="0.2s" fill="freeze" begin="0.6s"/>
  </line>

  <!--
    Animated cycling role text — 4 phrases, each shown for 2.5s, total cycle = 10s
    Timing per phrase: fade-in 0.4s, hold ~1.7s, fade-out 0.4s
    keyTimes align to: start-fade-in / end-fade-in / start-fade-out / end-fade-out / rest
  -->

  <!-- Phrase 1: FULL STACK DEVELOPER — starts at 1.2s -->
  <text x="430" y="152" font-family="'Courier New', monospace" font-size="15" fill="#00ff9c"
        text-anchor="middle" letter-spacing="6" opacity="0">
    FULL STACK DEVELOPER
    <animate attributeName="opacity"
      values="0;0.85;0.85;0;0"
      keyTimes="0;0.04;0.21;0.25;1"
      dur="10s" begin="1.2s" repeatCount="indefinite"/>
  </text>

  <!-- Phrase 2: AI / ML ENGINEER — starts at 1.2s + 2.5s = 3.7s offset, shown at 25% of cycle -->
  <text x="430" y="152" font-family="'Courier New', monospace" font-size="15" fill="#00ff9c"
        text-anchor="middle" letter-spacing="6" opacity="0">
    AI / ML ENGINEER
    <animate attributeName="opacity"
      values="0;0;0.85;0.85;0;0"
      keyTimes="0;0.25;0.29;0.46;0.5;1"
      dur="10s" begin="1.2s" repeatCount="indefinite"/>
  </text>

  <!-- Phrase 3: DEEP LEARNING — at 50% of cycle -->
  <text x="430" y="152" font-family="'Courier New', monospace" font-size="15" fill="#00ff9c"
        text-anchor="middle" letter-spacing="6" opacity="0">
    DEEP LEARNING
    <animate attributeName="opacity"
      values="0;0;0.85;0.85;0;0"
      keyTimes="0;0.5;0.54;0.71;0.75;1"
      dur="10s" begin="1.2s" repeatCount="indefinite"/>
  </text>

  <!-- Phrase 4: COMPUTER VISION — at 75% of cycle -->
  <text x="430" y="152" font-family="'Courier New', monospace" font-size="15" fill="#00ff9c"
        text-anchor="middle" letter-spacing="6" opacity="0">
    COMPUTER VISION
    <animate attributeName="opacity"
      values="0;0;0.85;0.85;0;0"
      keyTimes="0;0.75;0.79;0.96;1;1"
      dur="10s" begin="1.2s" repeatCount="indefinite"/>
  </text>

  <!-- Blinking cursor -->
  <rect x="416" y="95" width="3" height="18" fill="#00ff9c" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0;0.9" dur="0.8s" repeatCount="indefinite"/>
    <animate attributeName="x" values="416;590;590" dur="0.5s" fill="freeze" begin="0.3s"/>
  </rect>
</svg>
      
---

## 👨‍💻 About Me

```yaml
name:        Yashraj Agawane
role:        Full Stack Developer & AI/ML Engineer
education:   BTech IT – 3rd Year
location:    India 🇮🇳
focus:
  - Building production-grade full-stack applications
  - Deep Learning, Computer Vision & Intelligent Systems
  - Data Structures & Algorithms
  - AI-powered products that solve real-world problems
currently:   Building HireMind AI — an AI-powered recruitment platform
```

---

## ⚡ Tech Stack

<div align="left">

### 💻 Languages
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=yellow)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### 🌐 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### ⚙️ Backend & Databases
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### 🤖 AI / ML
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-FF6D00?style=for-the-badge&logo=groq&logoColor=white)

### 🚀 DevOps & Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 🚀 Featured Projects

<div align="center">

| 🏆 Project | 💡 Description | 🛠️ Stack | 🔗 |
|---|---|---|---|
| **🧠 HireMind AI** | AI-powered full-stack recruitment platform for students, job seekers & recruiters | Next.js · TypeScript · FastAPI · Gemini · Groq | [Repo](https://github.com/yashrajagawane) |
| **🏋️ AI Fitness Chatbot** | Generates personalized workout plans & nutrition guidance using Gemini AI | Next.js · TypeScript · Gemini API | [Repo](https://github.com/yashrajagawane/Fitness-Nutrition-Chatbot) |
| **🚗 Driver Drowsiness Detection** | Real-time driver monitoring via Eye Aspect Ratio (EAR) — triggers alert on fatigue | Python · OpenCV · Dlib · Flask | [Repo](https://github.com/yashrajagawane/driver-drowsiness-detection-system) |
| **🧬 Disease Prediction System** | Predicts multiple diseases from medical input data using classical ML models | Python · scikit-learn · Streamlit | [Repo](https://github.com/yashrajagawane/Multiple-Disease-Prediction-System) |

</div>

---

## 📊 GitHub Stats & Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=yashrajagawane&show_icons=true&theme=tokyonight&border_color=00FF9C&border_radius=12&hide_border=false&include_all_commits=true&count_private=true" height="180"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yashrajagawane&layout=compact&theme=tokyonight&border_color=00FF9C&border_radius=12&hide_border=false&langs_count=8" height="180"/>

<br/><br/>

<!-- Streak Stats -->
<img src="https://streak-stats.demolab.com?user=yashrajagawane&theme=tokyonight&border=00FF9C&ring=00FF9C&fire=FF6D00&currStreakLabel=00FF9C&border_radius=12" height="180"/>

<br/><br/>

<!-- Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=yashrajagawane&theme=tokyo-night&hide_border=false&border_color=00FF9C&color=00FF9C&line=00FF9C&point=FFFFFF&area=true&area_color=00FF9C" width="96%"/>

<br/><br/>

<!-- Contribution Stats (from your GitHub overview) -->
### 🎯 Contribution Breakdown
```
┌─────────────────────────────────────┐
│          Activity Overview          │
│                                     │
│   Commits        ████████░░  80%    │
│   Pull Requests  ██░░░░░░░░  20%    │
│   Code Review    ░░░░░░░░░░  —      │
│   Issues         ░░░░░░░░░░  —      │
└─────────────────────────────────────┘
```

</div>

---

## 🏅 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=yashrajagawane&theme=tokyonight&no-frame=false&no-bg=false&margin-w=6&row=1&column=7" width="96%"/>
</div>

---

## 🌐 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yashraj-agawane)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:agawaneyash865@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yashrajagawane)

</div>

---

<div align="center">

<!-- Footer wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00FF9C,100:0d1117&height=120&section=footer"/>

*⭐ "Build things. Break things. Learn things."*

</div>
