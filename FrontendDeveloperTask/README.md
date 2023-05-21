# ToDo App

## Tanım

Bu proje Simzet Yazılım LTD.ŞTİ. ön uç geliştirici alımı için taslak projedir. Geliştirici adayları bu projeyi klonlayıp geliştirip pull request atmaları gerekmektedir.

## Minimum Beklenen Özellikler
- Tüm proje tek "TodoTask.html" dosyası içerisinde bitirilmelidir.
- Proje dosyası içerisinde ek kütüphane veya çerçeve kullanılmadan js(ES6), css ve html kullanılarak geliştirme yapılmalıdır.
- "CheckList Custom Elementi Özellikleri" başlığı altındaki özelliklere uygun olarak bir checklist elementi geliştirilmelidir.
- "NavList Custom Elementi Özellikleri" başlığı altındaki özelliklere uygun olarak bir navlist elementi geliştirilmelidir.
- Tasarım responsive şekilde kodlanmalıdır.

## CheckList Custom Elementi Özellikleri
Örnek Kullanım : 	
    ``` <check-list baslik="Yapılacaklar" list="yaplist" placeholder="İş Açıklaması..."></check-list> ```
- Oluşacak satırların verisi html dosyasında yer alan veritabanı objesinden alınacaktır.
- Placeholder attribute değeri yeni eklenen satırlardaki inputun placeholder değerine atacaktır.Placeholder attribute verilmeyen checklist elementlerinde varsayılan değer "Yazınız..." olacaktır.
- Baslık attribute değeri checklistin içerisinde oluşacak baslik tagına yerleştirilecektir.
- Baslıkta yer alan yazdır butonuna basıldığında sadece o checklist elementinin dolu satırları gözükecektir.(Boş satırlar gizli olmalıdır.)
- Eklenen satırlarda input value değeri null ise solunda yer alan checkbox gizli olmalıdır.
- Yapıldı işaretlenen satırlarda text alanının üstü çizili olmaldır.
- Yapıldı işaretlenen satırlarda text input read only olmalıdır.
- Satırların sağında yer alan sil iconuna tıklandığında satır silinmelidir.

## NavList Custom Elementi Özellikleri
Örnek Kullanım : 	
    ``` <nav-list></nav-list> ```
- Satırlar html dosyasında yer alan veritabanı objesindeki kayıtlara göre otomatik oluşacaktır.
- Satırların innerHTML verisi o an domdaki list attribute ile eşleşen checklistten alacaktır.
- Scroll konumuna göre ekranda gözüken checklistin navlist karşılığı background style anlık olarak değişmelidir.
- Her satıra tıklandığında scroll ilgili checkliste kadar kaymalıdır.
- "Yeni Liste" butonuna basıldığında gözükecek inputa yazılacak değerle aynı başlık değerine sahip checklist elementi inputun sağında yer alan butona basıldığında anda oluşturmalı ve scroll oluşan liste gözükecek şekilde kaymalıdır.

## Ek Açıklama
 
 - Custom Element Kaynak : https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements
 - Verilen tasarımın birebir aynısı geliştirilmelidir.Temel tasarım yapısı bozulmadan yapılacak ek özellikler değerlendirmede hesaba katılır.
 - Projede yer alan kullanıcı adı ve profil fotografı gibi detaylar statik olabilir. Login altyapısı veya backend ile alakalı detayların geliştirilmesi beklenmemektedir.
 
## Örnek Proje Görselleri

[![Watch the video](https://dev.simzet.com/todotask/images/videokapak.png)](https://dev.simzet.com/todotask/images/screen-capture.webm)

![alt masaüstü](https://dev.simzet.com/todotask/images/Masaüstü1.png)

![alt mobil menü](https://dev.simzet.com/todotask/images/Mobilmenü.png)

![alt mobil](https://dev.simzet.com/todotask/images/Mobil.png)




## Geliştirici Notları

Buraya geliştirici projenin denenmesi için notlar ekleyebilir.
