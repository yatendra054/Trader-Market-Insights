# Market Sentiment & Trader Behavior Analysis

This repository contains the analysis and strategic findings from a study of two distinct datasets: **Trader Behavior** and **Market Sentiment**. The goal was to identify patterns in how traders act under different sentiment conditions—**Fear** and **Greed**—and to develop **data-driven trading strategies** based on these insights.

---

## Key Findings

### 1. Trading Volume
- **Fear Sentiment** involved significantly higher capital: **$79.6M vs. $57.0M** for Greed.
- **Insight**: Fear-driven traders move more money, indicating higher capital involvement during uncertain market periods.

### 2. Trade Direction (Buy/Sell Bias)
- **Fear Traders**: More **BUY-biased** (7,307 BUYs vs. 6,562 SELLs).
- **Greed Traders**: Slight **SELL bias** (5,407 BUYs vs. 5,885 SELLs).
- **Implication**: 
  - Fear often triggers *buying the dip* behavior.
  - Greed leads to *profit-taking* (selling).

### 3. Profitability
- Fear traders generated **more than double** the average profit per trade compared to greed traders.
- **Takeaway**: Challenges the assumption that greed-driven rallies are inherently more profitable.

### 4. Trading Costs
- Both groups pay **similar average fees**.
- **Fear Traders** incurred **slightly higher fees**, suggesting:
  - More **aggressive trade execution**
  - Use of **market orders** during high volatility

### 5. Hourly Activity Patterns
- Both sentiments show activity across the full day.
- **Fear sentiment peaks** at:
  - 03:00, 04:00, 08:00, 18:00, 23:00 UTC
- **These hours align with global market overlaps** (Asia, Europe, US).
- **Conclusion**: Fearful traders react to broader market events and volatility.

---

## Developed Strategies

### Capitalize on Greed/Extreme Greed Sentiment
- **Why**: Highest average profit per trade observed ($104.45).
- **Action**: Monitor sentiment indicators and deploy capital when greed is elevated.

### Avoid Trading During Extreme Fear
- **Why**: Despite high volume (208,898 trades), profit per trade was low ($49.27).
- **Action**: Risk-off approach — stay out of the market during these periods.

### Focus Trading Around High-Profit Hours
- **Why**: Peak profit per trade ($73.80) occurs at **18:00 UTC**.
- **Action**: Concentrate trading activity around this time using automated alerts.

---


## 📁 Repository Structure
Yatendra
├── notebook.ipynb
Needed
├── csv/
├── output/
Readme.md
Licence
