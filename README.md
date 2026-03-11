# 🚗 Carbiography

### Your Personal Automotive Timeline
<p align="center">
  <img src="/banner.png" alt="Carbiography Banner">
</p>
<p align="center">
<img src="https://img.shields.io/badge/status-prototype-blue">
<img src="https://img.shields.io/badge/made%20with-React-61DAFB">
<img src="https://img.shields.io/badge/style-Tailwind-38B2AC">
<img src="https://img.shields.io/badge/AI-Google%20Gemini-purple">
<img src="https://img.shields.io/badge/license-MIT-green">
<img src="https://img.shields.io/github/stars/yukselono/carbiography?style=social">
</p>
<p align="center">
<b>Carbiography is the Spotify Wrapped of
cars.</b><br>Track every vehicle you've driven,
owned, or experienced --- and turn it into deep insights, AI analysis,
and a beautiful shareable dashboard.
</p>

---

## ✨ What is Carbiography?

Carbiography is a highly interactive, beautifully designed, and deeply personalized automotive dashboard for car enthusiasts. With a sleek dark mode interface inspired by modern automotive dashboards, Carbiography acts as your personal digital garage log.

**It allows you to:**
* **Track** every vehicle you have ever driven.
* **Analyze** your lifetime driving statistics.
* **Discover** cultural insights about cars.
* **Generate** AI-powered automotive stories.
* **Share** your driving legacy with the world.

---

## 🚀 Key Features

### 📊 Deep Insights Dashboard
Your entire automotive life visualized in one dashboard. Carbiography automatically calculates:
- **Driver Score** & **Estimated Total Mileage**
- **CO₂ Carbon Debt**
- **Countries** you’ve driven in
- **Brand Loyalty** metrics & **Lifetime** driving statistics

### 📸 Wikipedia Vehicle Image Integration
Simply enter `Make + Model + Year`. Carbiography automatically retrieves high-quality images from Wikipedia to populate your garage visually.

### 🧠 AI Magazine Stories
*Powered by Google Gemini AI.*
With one click, generate a dramatic Top Gear-style magazine review blending real-world car prestige, technical specs, and your personal memories.
> *"The engine roared to life with the kind of mechanical symphony that makes enthusiasts grin like children."*

### 🎬 Pop Culture Intelligence
Your garage becomes part of automotive pop culture history. Carbiography analyzes your vehicles and reveals:
- **Global Rarity**
- Appearances in **Movies**
- Appearances in **Video Games** (including famous titles like *Forza Motorsport* & *Gran Turismo*)

### 🗓️ Driving Timeline & Vehicle Grid
Visualize your car history through multiple dynamic views:
* **Timeline Mode:** See vehicles in chronological order based on the year you drove them.
* **Garage Grid:** Filter vehicles by Brand, Segment, or Fuel Type.

### 📁 Smart Excel / CSV Import
Already have a car list? Import instantly using `.xlsx` or `.csv` formats. Powered by SheetJS, it's perfect for importing long driving histories in seconds.

### 📱 Shareable Social Cards
Export a stunning automotive summary card including your Name, Cars Driven, Total Mileage, Driver Score, and Environmental Footprint. Perfect for sharing on LinkedIn, Instagram, or X.

### ☁️ Global Voting *(Firebase)*
Carbiography includes a live **“Car of the Day”** voting system. Users worldwide can rate vehicles in real-time.

---

## 🛠️ Tech Stack

Carbiography is built as a **serverless, browser-native application**. It runs entirely in the browser—no backend required.

| Technology | Purpose |
| :--- | :--- |
| **HTML5 / CSS3** | Core structure |
| **JavaScript (ES6+)** | Logic & Interactivity |
| **React 18 (CDN)** | UI components |
| **Tailwind CSS** | Sleek, modern styling |
| **SheetJS** | Excel / CSV parsing |
| **html2canvas** | Share card generation |
| **Google Gemini API** | AI-generated stories |
| **Firebase** *(Optional)* | Cloud voting system |

---

## 🏁 Getting Started

One of the best parts of Carbiography is its **zero-setup architecture**. No build tools. No npm. No servers.

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/carbiography.git](https://github.com/yourusername/carbiography.git)
cd carbiography
```

### 2. Run Locally
Simply open `index.html` in your browser. That’s it! 
*(For development convenience, you can also use VSCode Live Server).*

### 3. Deploy with GitHub Pages
Since the app is fully static, deployment is instant:
1. Upload the repository to GitHub.
2. Go to **Settings → Pages**.
3. Select **Deploy from branch → main / root**.
4. Save. Your app will be live at: `https://username.github.io/carbiography`

---

## 📂 Demo Portfolio Feature

Want to see the dashboard populated instantly? Carbiography supports a demo data loader.

**Setup:** Place a file named `demo.xlsx` or `demo.csv` in the project root.
**Use:** Open the app and click **🏁 Try Demo Portfolio**. The dashboard will instantly populate with your demo data.

---

## ⚙️ Advanced Configurations

Carbiography works perfectly without APIs, but adding them unlocks powerful advanced features.

### 🤖 AI Stories (Google Gemini)
To enable AI articles:
1. Click **✨ Generate AI Article** in the app.
2. Enter your Gemini API key (Get a free key from [Google AI Studio](https://aistudio.google.com)).
*Note: The key is stored locally and securely in your browser.*

### ☁️ Global Voting (Firebase)
To enable the Car of the Day voting system:
1. Create a Firebase project and enable **Firestore**.
2. Enable **Anonymous Authentication**.
3. Update the config inside `index.html`:

```javascript
const fallbackConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID"
};
```

---

## 👨‍💻 Developer

**Created by Yiğit Yüksel** *Automotive enthusiast and technology builder.* 🔗 [LinkedIn Profile](https://linkedin.com/in/yigityuksel)

---

## ⭐ Support the Project

If you like the idea of Carbiography, consider:
- ⭐ **Starring** the repository
- 🚗 **Sharing** your own Carbiography dashboard
- 🧠 **Contributing** ideas and improvements

> **⚠️ Disclaimer:** Carbiography is an open-source concept project. Vehicle statistics, rarity estimates, and cultural references are based on public data and estimations.
