# HiFertility Mobile App

[![React Native](https://img.shields.io/badge/React%20Native-0.81-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-54-000020?style=flat-square&logo=expo&logoColor=white)](https://expo.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

The initial source snapshot of HiFertility, a fertility wellness mobile app with lessons, lifestyle tracking and a community space. The app content is mainly in Turkish.

> **The maintained version is [yigittozdemirr/hifertility](https://github.com/yigittozdemirr/hifertility).** It has the same application code, plus the native Android project, a downloadable APK, a demo video and full documentation.

## Features

- Courses and lessons with completion tracking
- Personal roadmap and Journey Garden
- Health data form and lifestyle tracker
- Homework and surveys
- Community forum, blog content and an expert consultation screen

## Tech stack

React Native, Expo, Expo Router, TypeScript, NativeWind and the Context API.

## Getting started

You need [Node.js](https://nodejs.org/) (LTS) and the [Expo Go](https://expo.dev/go) app or an emulator.

```bash
git clone https://github.com/yigittozdemirr/hifertility-mobile-app.git
cd hifertility-mobile-app/frontend
npm install
npm run dev
```

Scan the QR code with Expo Go on your device.

## Project structure

```text
.
├── frontend/      # Expo application
└── backend/       # Minimal Hono server template, not used by the app's screens
```

## Author

**Yiğit Özdemir**: [@yigittozdemirr](https://github.com/yigittozdemirr)
