*****Kahve Satış Verisi Analizi***** 

Bu proje, bir kahve dükkanı satış veri setini kullanarak veri temizleme, manipülasyon, analiz ve görselleştirme işlemlerini göstermektedir. 

***İçindekiler***

1.Giriş

2.Kurulum

3.İçerik Özeti

4.Özellikler   

**Giriş**

Bu proje, bir kahve dükkanı satış veri setini işleyip analiz ederek içgörüler elde etmeyi ve görselleştirmeler oluşturmayı hedefliyor. Proje kapsamında eksik veri yönetimi, sütun adlarının standartlaştırılması ve satış eğilimlerini anlamak için görselleştirmeler oluşturma yer alıyor. 

**Kurulum**

1-Bu depoyu yerel makinemize klonladık.

2-Aşağıdaki Python kütüphanelerini kurduk:  
- pandas, numpy, openpyxl, matplotlib, seaborn

3-Veri setini (Coffee Shop Sales.xlsx) uygun klasöre yerleştirdik.

**İçerik Özeti**

1-Başlangıç Kütüphanelerini Eklemek: Veri işleme ve görselleştirme için gerekli kütüphaneleri import ettik.

2-Veri Seti Yükleme ve İnceleme: Excel veri setini yükledik. Veri boyutunu, sütun/satır bilgilerini ve ilk/son birkaç satırı inceledik.

3-Veri Temizleme ve Manipülasyon: Eksik değerleri (NaN) tespit ettik ve sildik. Sütun isimlerini değiştirdik.

4-Veri Analizi ve Görselleştirme: Grupladık ve filtreledik. Satış verilerini görselleştirdik. Numerik sütunlar üzerinde yoğunluk analizleri yaptık.

5-Dönüşüm ve Hesaplama: Verileri farklı birimlere çevirdik(örneğin, dolar-türk lirası dönüşümü).

**Özellikler**

Veri Temizleme: Eksik değerleri işledik ve sütun adlarını standartlaştırdık. 

Analiz: Tanımlayıcı istatistikleri hesapladık. Kategorilere göre verileri gruplandırdık(örneğin, ürün türü, mağaza konumu). 

Görselleştirme: Fiyat dağılımları için bar ve KDE grafikleri oluşturduk. En çok satılan ürünler ve gelir eğilimleri için grafikler oluşturduk. 

Para Birimi Dönüşümü: Fiyatları USD'den TRY'ye dönüştürdük (örnek 1 USD = 34.55 TRY)

Kaggle linki: https://www.kaggle.com/code/zeyneppyildizz/turkish-ai-hub-veri-analizi
