# Reinforcement Learning - Dynamic Programming Implementation

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Repositori ini berisi implementasi algoritma **Dynamic Programming (DP)** untuk mengoperasikan *Reinforcement Learning* (RL) pada lingkungan terstruktur (*Markov Decision Process / MDP*). 

Metode DP di sini mengasumsikan bahwa agen memiliki **pengetahuan penuh terhadap model lingkungan** (transisi probabilitas $P$ dan *reward* $R$).

---

## 📌 Algoritma yang Diimplementasikan

Repositori ini mencakup dua teknik utama *Dynamic Programming* berdasarkan **Persamaan Ekspektasi Bellman**:

1. **Policy Iteration**
   - **Policy Evaluation**: Menghitung *state-value function* $V(s)$ secara iteratif untuk kebijakan ($\pi$) saat ini.
   - **Policy Improvement**: Memperbarui kebijakan secara *greedy* terhadap fungsi nilai yang baru dihitung hingga *policy* konvergen.
2. **Value Iteration**
   - Menggabungkan evaluasi dan peningkatkan kebijakan ke dalam satu langkah iterasi menggunakan **Bellman Optimality Equation**.
   - Secara langsung mengoptimalkan nilai $V^*(s)$ tanpa perlu melakukan evaluasi kebijakan hingga konvergen penuh di tiap tahapan.

---

## 🚀 Memulai (Getting Started)

### Prasyarat
Pastikan Python 3.8+ dan `pip` sudah terpasang di sistem Anda.

### Instalasi

1. **Clone repositori:**
   ```bash
   git clone [https://github.com/username-anda/nama-repo-anda.git](https://github.com/username-anda/nama-repo-anda.git)
   cd nama-repo-anda
