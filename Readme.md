<div align="center">

<!-- HERO WAVE BANNER -->
<img src="https://github.com/z0h1x/Glucoflow/blob/main/Assets/Banner.png" width="100%" alt="GlucoFlow Banner" />

<!-- ANIMATED SUBTITLE -->
<a href="https://glucoflowapp.vercel.app">
  <img src="https://readme-typing-svg.demolab.com?font=Plus+Jakarta+Sans&weight=700&size=18&duration=3200&pause=1100&color=10B981&center=true&vCenter=true&width=640&lines=Precision+Meal+%26+Correction+Bolus+Dosing;Basic+7-Slot+%26+Advanced+Glucose+Journal;Weekly+%26+Monthly+Trends+%2B+Doctor-Ready+PDF+Exports;Zero-Trust+Cloud+Sync+%E2%80%A2+EN+%2F+FR+%2F+AR+(RTL)" alt="GlucoFlow Capabilities" />
</a>

<br /><br />

<!-- PRIMARY CTA & WEBSITE BADGES -->
<a href="https://github.com/z0h1x/GlucoFlow/releases/latest">
  <img src="https://img.shields.io/badge/Download_APK-v1.5.3_(Build_8)-059669?style=for-the-badge&logo=android&logoColor=white" alt="Download GlucoFlow APK" />
</a>
<a href="https://glucoflowapp.vercel.app">
  <img src="https://img.shields.io/badge/Official_Website-glucoflowapp.vercel.app-1463F3?style=for-the-badge&logo=vercel&logoColor=white" alt="Official Website" />
</a>
<a href="https://z0h1x.vercel.app">
  <img src="https://img.shields.io/badge/Developer-Zohir_(@z0h1x)-091B3A?style=for-the-badge&logo=github&logoColor=white" alt="Developer Portfolio" />
</a>

<br />

<!-- LIVE GITHUB & PLATFORM BADGES -->
<a href="https://github.com/z0h1x/GlucoFlow/releases">
  <img src="https://img.shields.io/github/v/release/z0h1x/GlucoFlow?style=for-the-badge&color=0D9488&label=Latest%20Release" alt="Latest Release" />
</a>
<img src="https://img.shields.io/badge/Android-7.0%2B_(API_24–36)-3DDC84?style=for-the-badge&logo=android&logoColor=091B3A" alt="Android API 24+" />
<img src="https://img.shields.io/badge/Kotlin-Jetpack_Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin & Compose" />
<img src="https://img.shields.io/badge/Material_3-Clinical_Studio-1463F3?style=for-the-badge&logo=materialdesign&logoColor=white" alt="Material 3" />
<img src="https://img.shields.io/badge/Firebase-Auth_%26_Firestore-DD2C00?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase" />

<br /><br />

<p>
  <strong>GlucoFlow</strong> is a modern, clinical-grade Android diabetes management companion pairing a <strong>guided 5-step bolus insulin calculator</strong> with a <strong>dual-mode blood glucose journal</strong>, multi-range trend analytics, doctor-ready PDF exports, and SHA-256 verified OTA updates.
</p>

[Download Latest APK](https://github.com/z0h1x/GlucoFlow/releases/latest) •
[Official Website](https://glucoflowapp.vercel.app) •
[Clinical Engine](#-clinical-dosing-engine) •
[Tech Stack](#%EF%B8%8F-architecture--tech-stack) •
[Report an Issue](https://github.com/z0h1x/GlucoFlow/issues)

</div>

---

## ✨ Core Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧮 Guided 5-Step Bolus Calculator</h3>
      <img src="https://img.shields.io/badge/Dosing-Personalized_Rx-1463F3?style=flat-square" alt="Dosing" /><br /><br />
      <ul>
        <li><strong>Zero Hardcoded Defaults</strong> — Configured around your 6 prescribed ratios (Breakfast, Lunch & Dinner <code>CF</code> & <code>CR</code>).</li>
        <li><strong>Dual Correction Modes</strong> — Supports both <code>mg/dL per 1 U</code> and <code>U per 10 mg/dL</code>.</li>
        <li><strong>Smart Device Rounding</strong> — Precision rounding for <code>1.0 U</code> standard pens, <code>0.5 U</code> pediatric pens, <code>0.1 U</code> pumps, or custom steps.</li>
        <li><strong>Strict Clinical Units</strong> — Always measures in <code>mg/dL</code>, <code>g</code>, and <code>U</code> without silent unit conversions.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>📓 Dual-Mode Glucose Journal</h3>
      <img src="https://img.shields.io/badge/Logbook-Basic_%26_Advanced-0D9488?style=flat-square" alt="Logbook" /><br /><br />
      <ul>
        <li><strong>Basic Monitoring Sheet</strong> — Classic 7-slot daily grid (<em>Before / 2h After Breakfast, Lunch, Dinner & Bedtime</em>) with color-coded range stripes.</li>
        <li><strong>Advanced Meal Logbook</strong> — Log pre-meal & 2h post-meal glucose, food description, carbs, insulin brand, units, and dose time.</li>
        <li><strong>2-Hour Follow-Up Prompts</strong> — Highlights incomplete meals needing post-prandial readings.</li>
        <li><strong>Daily, Weekly & Monthly Views</strong> — Interactive monthly heatmap & range stats banner.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📈 Analytics & Clinical PDF Export</h3>
      <img src="https://img.shields.io/badge/Reports-Doctor_Ready_PDF-059669?style=flat-square" alt="Reports" /><br /><br />
      <ul>
        <li><strong>Weekly & Lifetime Status</strong> — Instant visual trend cards across 7-day, 30-day, and all-time horizons.</li>
        <li><strong>Custom Date-Range PDF</strong> — Generates clean clinical logbook tables tailored to Basic or Advanced mode.</li>
        <li><strong>One-Tap Share & Save</strong> — Print, save to device storage, or share directly with your endocrinologist or care team.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ Zero-Trust Cloud & Verified OTA</h3>
      <img src="https://img.shields.io/badge/Security-SHA256_%2B_Firestore-091B3A?style=flat-square" alt="Security" /><br /><br />
      <ul>
        <li><strong>Google Sign-In</strong> — One-tap authentication powered by Android Jetpack <code>CredentialManager</code>.</li>
        <li><strong>Private Cloud Sync</strong> — Real-time Firebase Firestore sync isolated per user UID with Room offline caching.</li>
        <li><strong>Verified In-App Updater</strong> — Checks GitHub Releases with strict <code>SHA-256</code> & APK signature verification.</li>
        <li><strong>Multilingual & Full RTL</strong> — Built natively in 🇬🇧 <strong>English</strong>, 🇫🇷 <strong>Français</strong>, and 🇲🇦 <strong>العربية (RTL)</strong>.</li>
      </ul>
    </td>
  </tr>
</table>

---

## 📲 Installation & Upgrading

### Fresh Install / Updating to `v1.5.3` (`com.z0h1xx.glucoflow`)

1. Open the [**Latest Release**](https://github.com/z0h1x/GlucoFlow/releases/latest) page.
2. Download **`GlucoFlow-v1.5.3-build8.apk`** from **Assets**.
3. Open the downloaded `.apk` file and allow installation from your browser/Files if prompted.
4. Sign in with your Google account — your profile, insulin ratios, calculation history, and journal entries restore automatically.

> [!IMPORTANT]
> **Upgrading from older `v1.5` builds?**
> Starting from **v1.5.1+**, GlucoFlow uses the dedicated package ID **`com.z0h1xx.glucoflow`**. When opening the new release for the first time, GlucoFlow automatically detects if the older package is still installed and guides you to uninstall it so you don't end up with duplicate apps. All of your cloud data remains safely preserved in Firebase.

---

## 🧮 Clinical Dosing Engine

<details>
<summary><strong>Click to inspect exact mathematical formulas & safety constraints</strong></summary>

<br />

All calculations execute deterministically using the user's clinician-prescribed ratios for the selected meal (`Breakfast`, `Lunch`, or `Dinner`):

| Component | Mode `mg/dL per 1 U` | Mode `U per 10 mg/dL` | Rounding Behavior |
| :--- | :--- | :--- | :--- |
| **Correction Dose** | `max(0, (Current - Target) / CF)` | `max(0, (Current - Target) × CF / 10)` | Rounded independently to device increment |
| **Meal (Food) Dose** | `(Carbs × CR) / 10` | `(Carbs × CR) / 10` | Rounded independently to device increment |
| **Total Bolus Dose** | `Round(Correction) + Round(Meal)` | `Round(Correction) + Round(Meal)` | Half-up clinical rounding (`floor(x + 0.5)`) |

- Glucose entries are strictly bounded (`0 – 1000 mg/dL`), target glucose must be `> 0 mg/dL`, and correction dose clamps cleanly at `0.0 U` when current glucose is at or below target.
- The **Glucose Journal** is strictly manual and never auto-imports calculator estimates, keeping clinical logbooks authentic.

</details>

---

## 🛠️ Architecture & Tech Stack

```text
GlucoFlow/
├── app/src/main/java/com/example/
│   ├── domain/          # Pure Kotlin BolusCalculatorEngine, models & trend analyzers
│   ├── data/            # CredentialManager Google Auth, Firestore repositories & offline store
│   ├── journal/         # Basic/Advanced logbook state, Room/Cloud sync & PdfDocument exporter
│   ├── update/          # GitHub Releases API client, SHA-256 & APK signing cert verifier
│   └── ui/
│       ├── theme/       # Clinical Studio Design System (Midnight Navy, Cobalt, Teal, Jakarta/Mono fonts)
│       ├── components/  # Reusable M3 cards, 3D pen/pump showcase, weekly/lifetime charts
│       └── screens/     # AuthScreen, Onboarding, Calculator, Journal, History & Settings
└── firestore.rules      # Zero-trust per-user Firebase Firestore security rules
```

| Layer | Technology |
| :--- | :--- |
| **UI Framework** | Kotlin • Jetpack Compose • Material Design 3 • Adaptive Window Size Classes |
| **State & Concurrency** | MVVM • `StateFlow` • Kotlin Coroutines • Navigation Compose |
| **Cloud & Auth** | Firebase Authentication • Google Credential Manager • Cloud Firestore |
| **Graphics & Export** | Custom Canvas Charts • Android `PdfDocument` • Custom Adaptive Icon |
| **Quality Assurance** | JUnit 4 • Robolectric UI & End-to-End Tests • Firestore Emulator Rules Suite |

### Build & Test Locally

```bash
# Run all unit & Robolectric UI tests
gradle :app:testDebugUnitTest

# Build debug APK
gradle :app:assembleDebug
```

---

## ⚠️ Medical Disclaimer

> GlucoFlow is a **clinical decision-support and diabetes logging aid** designed around parameters prescribed by your healthcare provider. It does **not** replace professional medical judgment. Always verify insulin calculations and discuss adjustments to your Correction Factors (`CF`), Carbohydrate Ratios (`CR`), or target glucose ranges with your endocrinologist or diabetes care team.

---

<div align="center">

### 💬 Need Help or Have Feedback?

<a href="https://glucoflowapp.vercel.app">
  <img src="https://img.shields.io/badge/🌐_Website-glucoflowapp.vercel.app-1463F3?style=for-the-badge" alt="Website" />
</a>
<a href="https://z0h1x.vercel.app">
  <img src="https://img.shields.io/badge/👨‍💻_Developer-z0h1x.vercel.app-091B3A?style=for-the-badge" alt="Developer" />
</a>
<a href="https://github.com/z0h1x/GlucoFlow/releases">
  <img src="https://img.shields.io/badge/📦_Releases-GitHub_APK-059669?style=for-the-badge" alt="Releases" />
</a>

<br /><br />

<sub>Built with care by <strong>Zohir (@z0h1x)</strong> • © 2026 Zohir • GlucoFlow. All rights reserved.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D9488,50:1463F3,100:091B3A&height=110&section=footer" width="100%" alt="GlucoFlow Footer" />

</div>
