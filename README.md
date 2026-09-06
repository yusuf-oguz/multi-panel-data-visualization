# Four Data Visualization Problems

<details>
<summary>🇹🇷 Türkçe özet için tıklayın</summary>

Dört farklı problem, farklı veri setleri üzerinde çeşitli grafik tekniklerini kapsıyor.

**Problem 1:** en popüler dilimin otomatik tespit edilip öne çıkarıldığı (pulled slice) ve grafik başlığına yansıtıldığı bir pasta grafiği (favori video oyunu karakterleri).
**Problem 2:** dünya genelindeki yıllık kurumsal yapay zeka yatırımını gösteren bir çizgi grafik.
**Problem 3:** yapay zeka modellerinin 2012-2024 arası hesaplama gücü ölçeklenmesini analiz eden, 4 panelli bir figür.
**Problem 4:** oyuncu özniteliklerini donut chart, yığın dağılım grafiği (swarm scatter) ve paralel koordinatlar grafiğiyle inceleyen 3 panelli bir görselleştirme.

**Kapsam:** dört veri setini görselleştiren odaklı bir egzersiz, modelleme veya pipeline çalışması içermiyor.

</details>

---

Four unrelated problems, each pairing a dataset with a different charting technique.

**Scope:** a focused visualization exercise across four datasets, no modeling or pipeline work involved.

## Problem 1: favorite video game characters

A pie chart where the most popular slice is detected automatically and pulled out, with the chart title updating to match.

## Problem 2: global corporate AI investment

A line chart built from `corporate-investment-in-artificial-intelligence-total.csv`, tracking worldwide corporate AI investment year by year.

## Problem 3: AI compute scaling, 2012-2024

A four-panel figure built from `ai_compute_scaling.csv`, analyzing how the compute used to train AI models scaled between 2012 and 2024.

## Problem 4: player attributes

A three-panel visualization built from `player_attributes.csv`: a donut chart, a swarm scatter plot, and a parallel coordinates plot.

## Files

| File | What it is |
|---|---|
| `visualizations.ipynb` | All four solutions |
| `data/` | The three datasets (AI investment, AI compute scaling, player attributes) |
| `ai_scaling_analysis.png` | The rendered output for Problem 3 |

## Tools

Python, Pandas, Matplotlib, NumPy.
