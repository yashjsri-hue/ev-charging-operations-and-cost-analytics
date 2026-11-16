# VoltGrid – EV Charging Operations & Cost Analytics

## Project Overview

VoltGrid is an Electric Vehicle (EV) Charging Operations & Cost Analytics project developed using **Microsoft Power BI**. The project focuses on analysing EV charging sessions, vehicle performance, energy consumption, charging costs, charger utilisation and location-wise charging activity.

The objective is to transform raw charging data into meaningful business insights that help organisations understand charging patterns, monitor electricity expenditure and improve charging operations.

## Business Problem

EV charging operators face several operational challenges:

- Understanding charging demand across different vehicle models.
- Identifying which charger types consume the most electricity.
- Monitoring charging activity across different locations.
- Evaluating electricity consumption and charging expenditure.
- Understanding battery State of Charge (SOC) improvements.
- Identifying opportunities to improve charging efficiency and manage operating costs.

## Project Objectives

1. Analyse charging sessions across different EV models.
2. Compare energy consumption across charger types.
3. Identify locations with the highest charging activity.
4. Examine charging patterns across different days of the week.
5. Compare starting and ending battery State of Charge.
6. Analyse charging expenditure across different locations.
7. Develop actionable recommendations to improve charging operations.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Data modelling, DAX calculations and dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and analytical measures |
| CSV | Dataset storage and input |

## Dataset Description

**Dataset:** `voltgrid_ev_charging_cleaned.csv`

The cleaned dataset contains EV charging session records covering vehicle models, charger types, charging locations, energy consumption, charging duration, charging rates, charging costs and battery State of Charge.

The dataset is used to evaluate charging operations and identify business performance patterns.

## Key Performance Indicators (KPIs)

The executive dashboard includes the following KPIs:

| KPI | Value | Business Purpose |
|---|---:|---|
| Total Charging Sessions | 1,320 | Measures overall charging activity |
| Total Energy Consumed | 53.47K kWh | Measures total electricity consumption |
| Total Charging Cost | $29.77K | Measures overall charging expenditure |
| Average Charging Rate | 25.96 kW | Measures average charging power |
| Average Charging Duration | 2.27 hours | Measures average session duration |

Additional analytical measures include Average Cost per kWh and Average Energy Consumption per Session.

## Power BI Dashboard & Visualizations

The executive dashboard contains six data-supported visualizations:

### 1. Charging Sessions by Vehicle Model
**Business Question:** Which EV models contribute the most and least to total charging activity?

Analyses charging session distribution across Tesla Model 3, Hyundai Kona, Nissan Leaf, BMW i3 and Chevy Bolt.

### 2. Energy Consumption by Charger Type
**Business Question:** Which charger type accounts for the highest electricity consumption?

Compares energy consumption across Level 1, Level 2 and DC Fast Chargers to understand charger-wise electricity demand.

### 3. Charging Sessions by Location
**Business Question:** Which locations experience the highest charging activity?

Identifies differences in charging demand across Los Angeles, San Francisco, Houston, Chicago and New York.

### 4. Charging Activity by Day of Week
**Business Question:** How is charging activity distributed across different days of the week?

Examines daily charging patterns to understand variations in charging activity throughout the week.

### 5. Starting vs Ending State of Charge
**Business Question:** How does the average battery charge level change between the beginning and end of charging sessions?

Compares average starting and ending battery State of Charge across different EV models to evaluate charging outcomes.

### 6. Charging Cost by Location
**Business Question:** Which locations contribute the most to overall EV charging expenditure?

Compares location-wise charging costs to identify areas requiring closer monitoring of electricity expenditure.

## Key Business Insights

- Tesla Model 3 records the highest charging activity among the five vehicle models.
- Level 2 chargers account for the highest energy consumption.
- Los Angeles records the highest number of charging sessions.
- Charging activity remains relatively consistent across weekdays.
- Average ending State of Charge is considerably higher than average starting State of Charge across all vehicle models.
- Los Angeles records the highest charging expenditure, at approximately $6.69K.

## Business Recommendations

1. **Vehicle-wise Charging Monitoring:** Monitor charging demand across vehicle models to maintain appropriate charging infrastructure availability.

2. **Charger Utilisation Optimisation:** Evaluate energy consumption and operating costs across charger types to improve infrastructure utilisation.

3. **Location-based Resource Allocation:** Prioritise operational monitoring and charging infrastructure planning in locations with higher charging activity.

4. **Charging Schedule Management:** Maintain charging availability throughout the week and investigate peak-hour demand to improve operational planning.

5. **Battery Charging Performance:** Monitor starting and ending State of Charge to identify unusual charging outcomes and improve charging performance.

6. **Charging Cost Optimisation:** Compare electricity expenditure and cost per kWh across locations to identify opportunities for reducing charging expenses.

## Project Deliverables

| File | Description |
|---|---|
| `Executive_Dashboard.png` | Power BI executive dashboard screenshot |
| `VEV_FODPA1.pbix` | Interactive Power BI dashboard file |
| `voltgrid_ev_charging_cleaned.csv` | Cleaned EV charging dataset |
| `KPI_Calculations.docx` | KPI calculation explanations |
| `Recommendation_Justification.docx` | Justification for business recommendations |

## Repository Structure

```text
ev-charging-operations-and-cost-analytics/
│
├── .gitignore
├── Executive_Dashboard.png
├── KPI_Calculations.docx
├── Recommendation_Justification.docx
├── VEV_FODPA1.pbix
├── voltgrid_ev_charging_cleaned.csv
└── README.md
```

## Expected Business Outcomes

This project demonstrates how Power BI can transform EV charging data into actionable operational insights.

The analysis supports:

- Better understanding of EV charging demand.
- Improved visibility into vehicle and charger performance.
- Location-wise monitoring of charging operations.
- Better tracking of electricity consumption and expenditure.
- Data-driven charging infrastructure and cost management decisions.

## Conclusion

VoltGrid – EV Charging Operations & Cost Analytics demonstrates the application of Power BI, Power Query and DAX to a practical business analytics problem.

By analysing charging sessions, vehicle models, charger types, locations, battery performance and electricity expenditure, the project provides meaningful insights and actionable recommendations to support more efficient EV charging operations.

---

**Project Category:** Data Analytics | Business Intelligence | Electric Vehicle Analytics

**Tools Used:** Microsoft Power BI, Power Query, DAX, CSV

**Developed by:** [yashjsri-hue](https://github.com/yashjsri-hue)