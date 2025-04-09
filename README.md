# 🎮 Gamer Performance Analyzer
**By Zuhayr Chowdhury**

This project analyzes 60 days of gameplay session data to answer a fundamental question many gamers face:  
> **"Am I actually getting better, or just playing more?"**

The goal was to uncover whether improved performance comes from skill development or simply putting in more hours — by examining in-game metrics like K/D ratio, win rate, mood, and session length.

---

## 🎯 Project Objective

To analyze personal gaming performance across multiple dimensions — time, mood, and game type — and visualize whether improvement is based on **skill progression** or just **habitual grinding**.

This project also serves to showcase data analytics skills across the full pipeline:
- **Data generation**
- **SQL-based insights**
- **Interactive data visualization**

---

## 🛠️ Tools Used

| Tool       | Purpose                                      |
|------------|----------------------------------------------|
| **Python** | Simulated realistic gamer session data over 60 days (since no public game data APIs were used) |
| **SQLite + SQL** | Structured and queried data to uncover performance trends and behavioral patterns |
| **Tableau** | Built a clean dashboard to visualize skill vs. grind, mood impacts, and fatigue effects |

---

## 🧪 How the Data Was Created

Since detailed personal gameplay data wasn’t available via APIs, I created a custom **Python script** to simulate realistic gamer sessions across games like *Apex Legends*, *Valorant*, and *Overwatch*. Each session included:
- Date
- Game played
- Session length (hours)
- Matches played, kills, deaths, win count
- Calculated K/D ratio
- Self-reported mood

The script mimics real gamer behavior by randomizing patterns while embedding logic like:
- More playtime on weekends
- Mood fluctuation after long sessions
- Performance variation by game

This simulated data was saved to a CSV and used throughout the analysis.

---

## 📈 Key Insights

- 🎯 **Apex Legends** had the highest K/D ratio (9.33), despite not being the most played — suggesting higher efficiency.
- 🎭 **Focused mood** correlated with the highest win rate (~60%).
- ⏳ **Longer sessions** didn’t always result in better win rates — performance tended to plateau or decline after 3+ hours.
- 📅 Most sessions occurred on **Sundays and Mondays**, revealing personal gaming patterns.
- 🔥 **Overwatch** was the most played, but with relatively lower performance, indicating potential "grind without gain."

---

## 📊 Dashboard Preview

![Dashboard](images/dashboard_preview.png)

📌 [View Full Dashboard on Tableau Public](https://public.tableau.com/app/profile/zuhayr.chowdhury4285/viz/GamingAnalysis_17441877582240/GamerPerformanceAnalyze)

---

## 📁 Files Included

- `/data`: CSV of simulated gamer sessions
- `/notebooks`: Python notebooks for data generation and SQL analysis
- `/images`: Dashboard screenshots
- `/dashboard`: Exported Tableau dashboard as PDF or TWBX

---

## 💡 What I Learned

- How to design a realistic simulation of user data when APIs are unavailable
- How to structure and analyze data using SQL to extract behavioral insights
- How to build an interactive Tableau dashboard with focused storytelling
- The value of combining mood/emotion data with performance metrics in personal analytics

---
