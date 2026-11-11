# 💸 Expense Tracker

A mobile expense tracking app for Android, built with HTML/CSS/JavaScript and packaged with [Capacitor](https://capacitorjs.com). Works fully offline, with a dark Arabic (RTL) interface.

## ✨ Features

- Add expenses quickly with amount, category, note, and date
- Monthly budget with daily average and progress bar
- Spending breakdown chart by category
- Search and filter expenses by category
- Browse previous and next months
- Export expenses to **CSV** (opens in Excel or Google Sheets)
- Full **JSON backup** and restore
- Installable as a PWA and works offline
- Responsive layout designed for phones

## 🛠 Built with

- HTML, CSS, vanilla JavaScript
- Capacitor (Android wrapper)
- Service Worker + Web App Manifest

## 🚀 Run it

**In the browser:** serve the `www` folder over HTTPS (for example with GitHub Pages) and open it.

**As an Android app:**

1. Install Node.js and Android Studio
2. Clone this repository and run `npm install`
3. Run `npx cap sync`
4. Run `npx cap open android`
5. In Android Studio: Build > Generate App Bundles or APKs > Generate APKs

## 💾 Data storage

Data is currently stored locally on the device. Use **Settings > Backup** regularly to keep a copy of your data.

## 🗺 Roadmap

- [ ] SQLite storage
- [ ] Reliable file export and share on Android
- [ ] Cloud sync

## 👤 Author

Made by [Youssef](https://github.com/youssef6253)
