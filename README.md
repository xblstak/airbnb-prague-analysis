# Analýza Airbnb ubytovaní v Prahe

Projekt sa zameriava na spracovanie, analýzu a vizualizáciu dát z platformy Airbnb v meste Praha. Súčasťou projektu je práca s geografickými údajmi, štatistická analýza a analýza sentimentu používateľských recenzií.

## Cieľ projektu

Cieľom bolo získať zaujímavé poznatky o ponuke Airbnb ubytovaniach v Prahe pomocou dátovej analýzy a geoinformatických nástrojov.

Projekt zahŕňa:

- čistenie a úpravu dát,
- prácu s geografickými údajmi,
- tvorbu štatistík a vizualizácií,
- analýzu používateľských recenzií,
- sentiment analýzu textov.

## Použité technológie

- Python
- Pandas
- NumPy
- GeoPandas
- Matplotlib
- Seaborn
- Shapely
- VADER Sentiment Analysis
- Fast Language Detection

## Použité datasety

Projekt pracuje s tromi datasetmi:

- `listings.csv` – informácie o jednotlivých ubytovaniach
- `reviews.csv` – používateľské recenzie
- `neighbourhoods.geojson` – geografické hranice mestských častí

## Obsah projektu

### Spracovanie dát

- načítanie dát zo súborov CSV a GeoJSON,
- identifikácia a odstránenie chýbajúcich údajov,
- prevod dátových typov,
- filtrovanie nekonzistentných záznamov.

### Prieskumná analýza dát

V rámci projektu boli analyzované napríklad:

- ceny ubytovaní,
- dostupnosť ubytovaní,
- počet recenzií,
- aktivita hostiteľov,
- rozdelenie ubytovaní medzi mestské časti.

### Geografická analýza

Pomocou GeoPandas boli vytvorené mapové vizualizácie zobrazujúce:

- rozloženie Airbnb ubytovaní,
- hustotu ubytovaní,
- štatistiky jednotlivých mestských častí.

### Analýza sentimentu

Recenzie boli analyzované s cieľom zistiť:

- jazyk recenzie,
- pozitívny alebo negatívny sentiment,
- rozdiely medzi jednotlivými mestskými časťami.

## Výsledok

Projekt poskytuje prehľad o fungovaní Airbnb v Prahe a ukazuje možnosti kombinácie dátovej analýzy, geografických dát a spracovania prirodzeného jazyka.
