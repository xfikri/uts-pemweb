# UTS PEMWEB
### Oleh
## 20230801529 - MUHAMMAD FIKRI NUR WAHID
# PROSES SLR (Systematic Literature Review)
Rumpun Ilmu: Teknik Informatika dengan Peminatan Artificial Intelligence - Machine Learning

Detail: Menerapkan Algoritma Prediksi untuk Optimasi Bisnis Coffee Shop

P (Platform/System/Users):

Web Application untuk Dashboard Pemilik Coffee Shop

Sistem Recommendation untuk Customer

Dataset: Transaksi Penjualan, Data Customer, Inventory

I (Technology Intervention):

Algoritma Machine Learning (Clustering untuk Segmentasi Customer, Time Series Forecasting untuk Prediksi Penjualan, Recommendation System)

Python FastAPI untuk ML Model Serving

PHP/Laravel Filament untuk Admin Dashboard

MySQL Database

C (Alternate Technology/Baseline):

Sistem Manual (Excel-based reporting)

Traditional Inventory Management

Tidak ada personalized recommendation

O (Outcome/Performance Matriks):

Akurasi prediksi penjualan (MAPE, RMSE)

Precision/Recall recommendation system

Peningkatan customer satisfaction

Pengurangan food waste

Peningkatan revenue

S (Study Design/Evaluation Method):

A/B Testing untuk recommendation system

Cross-validation untuk model prediksi

Kuesioner kepuasan pelanggan

Analisis ROI (Return on Investment)

# PROSES RQ
bash
RQ 1: RESEARCH QUESTION 1: ANALISIS AKURASI ALGORITMA MACHINE LEARNING
"Bagaimana tingkat akurasi dan efektivitas algoritma machine learning dalam mengklasifikasikan pola produktivitas pengguna ke dalam kategori 'Sehat' atau 'Berpotensi Toksik' berdasarkan data perilaku kerja yang dikumpulkan?"

Penjelasan: Research question ini berfokus pada aspek teknis implementasi machine learning, dimana peneliti akan mengevaluasi kemampuan berbagai algoritma classification (seperti Random Forest, SVM, atau Neural Networks) dan clustering (seperti K-Means atau DBSCAN) dalam mengidentifikasi pola kerja yang tidak sehat. Efektivitas diukur melalui metrik standar machine learning seperti accuracy, precision, recall, dan F1-score, dengan tujuan menemukan model terbaik yang dapat secara konsisten membedakan antara pola kerja yang produktif-sehat versus yang berpotensi menyebabkan burnout atau dampak negatif lainnya.

RQ 2:RESEARCH QUESTION 2: OPTIMASI VISUALISASI INSIGHT PRODUKTIVITAS
"Bentuk visualisasi data seperti apa yang paling mudah dipahami dan actionable bagi pengguna dalam menyajikan insight mengenai pola produktivitas mereka, khususnya dalam mengidentifikasi pola kerja yang berpotensi toksik?"

Penjelasan: Research question ini berfokus pada aspek user experience dan presentasi data, dimana peneliti akan mengeksplorasi berbagai format visualisasi (seperti heatmap distribusi waktu kerja, grafik tren produktivitas, radar chart keseimbangan kehidupan kerja, atau alert system untuk pola berbahaya) untuk menentukan mana yang paling efektif dalam meningkatkan kesadaran pengguna. Keberhasilan dinilai melalui user testing yang mengukur comprehensibility, actionability, dan dampak terhadap perubahan perilaku kerja, dengan tujuan menciptakan dashboard insights yang tidak hanya informatif tetapi juga memotivasi pengguna untuk memperbaiki kebiasaan kerja mereka.

KEYWORD UNTUK PENCARIAN JURNAL
Kelompok 1: Klasifikasi & Deteksi Pola Produktivitas
sql
("productivity monitoring" OR "work behavior analysis" OR "employee monitoring") 
AND 
("machine learning classification" OR "pattern recognition" OR "behavioral clustering") 
AND 
("burnout detection" OR "toxic work pattern" OR "mental health monitoring" OR "work fatigue detection")
AND 
("supervised learning" OR "unsupervised learning" OR "behavioral analytics")
Kelompok 2: Metrik Evaluasi Algorithm ML
sql
("model accuracy" OR "classification performance" OR "algorithm effectiveness") 
AND 
("precision recall" OR "F1-score" OR "confusion matrix" OR "cross-validation")
AND 
("Random Forest" OR "SVM" OR "Neural Networks" OR "K-Means clustering")
AND 
("performance metrics" OR "model evaluation" OR "predictive accuracy")
Kelompok 3: Visualisasi Data & Dashboard Insights
sql
("data visualization" OR "dashboard design" OR "analytics interface") 
AND 
("user understanding" OR "comprehensibility" OR "actionable insights")
AND 
("information visualization" OR "visual analytics" OR "interactive dashboard")
AND 
("user experience" OR "UX design" OR "human-computer interaction")
Kelompok 4: Aplikasi dalam Konteks Produktivitas
sql
("workplace analytics" OR "employee productivity" OR "digital wellbeing") 
AND 
("behavior change" OR "intervention design" OR "feedback systems")
AND 
("personal informatics" OR "self-monitoring" OR "quantified self")
AND 
("health monitoring" OR "wellbeing technology" OR "preventive systems")
STRATEGI PENCARIAN LANJUT
Boolean Combinations untuk Pencarian Mendalam:
sql
("machine learning classification" AND "productivity monitoring" AND "visualization dashboard")
OR
("behavioral pattern recognition" AND "workplace analytics" AND "user interface design")
OR
("burnout prediction" AND "data visualization" AND "employee wellbeing")


terlampir file SLR dengan nama SLR.pdf

# BRD

terlampir file BRD berdasarkan SLR dengan nama file BRD.pdf

# IMPLEMENTASI WEBSITE
```
1. cd /root/boilerplate
2. ./start.sh uts-pemweb
3. cd /root/perkuliahan/uts-pemweb
4. cd src
5. code .
6. https://themewagon.com/themes/coffo/
6. cd resource/views
8. mkdir layouts && mkdir pages && mkdir partials
9. cd ../../routes/