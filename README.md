# Singapore Retail: A Decade of Change

## Project Overview

How has Singapore's retail landscape changed, and which retail categories have recovered or grown differently since the pandemic?

This project analyses Singapore's annual Retail Sales Index (RSI) to explore changes in overall retail performance and differences across retail categories. Using Tableau, I built an interactive dashboard to compare long-term trends, benchmark category performance, and examine how the retail landscape has evolved since 2019.

## Key Findings

* **Overall retail sales value index remains above its 2017 baseline.** In 2025, the total index reached approximately 107, compared with the 2017 baseline of 100.
* **Performance varies substantially across categories.** Watches & Jewellery and Computer & Telecommunications Equipment recorded some of the strongest increases relative to 2017.
* **The recovery has not been uniform.** By 2025, some categories remained below their 2019 levels, including Department Stores.
* **The choice of baseline matters.** Comparing categories against both 2017 and 2019 helps distinguish longer-term changes from post-pandemic recovery patterns.

## Dashboard

The Tableau dashboard explores four perspectives:

1. **Overall trend (2017–2025):** How Singapore's total retail sales index changed over time.
2. **Category comparison:** Which retail categories performed above or below the 2017 baseline.
3. **Category trends:** How individual retail categories evolved over the observed period.
4. **Post-pandemic comparison:** How category performance in 2025 compares with 2019.

**Dashboard preview:** ![Dashboard Preview](images/Singapore%20Retail%20Dashboard.png)

## Data & Methodology

* **Source:** Singapore Retail Sales Index, annual data at current prices.
* **Coverage:** 1985–2025, with historical availability varying by category.
* **Index baseline:** 2017 = 100.
* **Tool:** Tableau.
* **Approach:** Trend analysis, category ranking, and baseline comparisons.

The analysis uses descriptive comparisons to identify patterns across time and categories. It does not attempt to establish causal relationships.

## Important Caveats

* The index is measured at current prices, so changes reflect both price and quantity movements; they should not be interpreted as changes in sales volume alone.
* Missing observations are treated as unavailable data, not as zero.
* Historical coverage differs across categories, so comparisons should account for the years available.
* The findings describe observed patterns and do not establish why a category changed.

## Files

* `Singapore_Retail_Dashboard.twbx` — packaged Tableau workbook, including its data extract.
* `data/` — original dataset.
* `images/` — dashboard screenshots.

## Skills Demonstrated

* Tableau dashboard design and data visualisation
* Exploratory data analysis
* Time-series and category-level comparisons
* KPI and baseline selection
* Translating quantitative findings into a concise business narrative
