# Terminal-CheatSheet

Bu repoda Linux terminal ortamında genel olarak kullandığım, bildiğim kmomutlara yer verdim. Herhangi bir yanlışlık var ise pull request'e açıktır.

## Temel Komutlar

` pwd`: Şu an bulunduğunuz dizini yazdırır.

` cd dizin_adı`: Bulunduğunuz dizini değiştirmeyi sağlar. dizin_adı adlı dizine gider.

` cd -`: Bulunduğunuz dizinden bir önceki dizine döner.

` cd ..`: Bulunduğunuz dizinden bir üst dizine döner.

` ls`: Bulunduğunuz dizinin içerisindeki dosyaları ve dizinleri listeler.

` ls -R`: Bütün klasörleri ve içindekileri gösterir.

` cat dosya_adı`: Dosyanın içeriğini ekrana yazdırır. 

` cp`: Mevcut dizinden dosya kopyalar.

` mv`: Dosyaları taşımak ya da yeniden adlandırmak için kullanılır.

` rm`: Dosyaları silmek için kullanılır.

` mkdir`:Yeni bir dizin oluşturmak için kullanılır.

` rmdir`: Dizin silmek için kullanılır.

` rm`: Dizinleri içindekilerle birlikte silmek için kullanılır.

` locate`: Bir dosyanın konumunu bulmak için kullanılır.

` find`: Locate komutuna benzerdir. Farkı ise belirli bir dizinde dosyalar bulmak için kullanılmasıdır.

` grep`: Belirli bir dosyadaki metinde arama yapmak için kullanılır.

` df`: Sistemin disk alanı kullanımını yüzdesel ve kb olarak öğrenmek için kullanılabilir.

` du`: Bir dosyanın veya dizinin ne kadar alan kapladığını kontrol etmek için kullanılır.

` diff`: İki dosyanın içeriğini satır satır karşılaştırır. 

` wget`: Bu komut aracılığıyla internetten dosya indirebilirsiniz. `wget dosya_bağlantısı`  

` history`: Son kullanılan komutları listelemek için kullanılır.

` man`: herhangi bir komutun nasıl kullanılacağını öğrenmek için kullanılır.

` echo`: Bir dosyaya veri taşımak için kullanılır.

` zip`: Dosyaları sıkıştırmak için kullanılır.

`unzip`: Dosyaları zip arşivinden kurtarmak için kullanılır.


## Sistem

`who`: Oturum açmış kullanıcıları listelemek için kullanılır.

` ~ ` : Oturumun sahibi kullanıcı için home dizinini gösterir.

` su`: Başka bir kullanıcının yetkileri ile komut çalıştırmak için kullanılır.

` sudo`: Yönetici veya kök izinlerini gerektiren görevleri yapmanıza izin verir.

`ps`: Sisteminizde hangi işlemlerin çalıştığını görmenizi sağlar.

` kill`: Yanıt vermeyen programları bu komut yardımıyla elle sonlandırabilirsiniz.

` ping`: Bir sunucuya bağlantınızı kontrol etmek için kullanılır.

` top`: Çalışmakta olan programların listesini ve bu programların ne kadar cpu kullandığını gösterir.

`free`: RAM kullanımı ve durumu ile ilgili bilgi almak için kullanılır.

`lsblk`: Sistemdeki diskleri ve partitionları görmek için kuallnılır.

`lsusb`: USB aygıtları listelemek için kullanılır.

` hostname`: Host’un veya ağın adını öğrenmek için kullanılır.

` hostname -I`: Ip adresini öğrenmek için kullanılır.

` useradd`: Sisteme yeni bir kullanıcı eklemek için kullanılır.

` passwd`: Sistem kullanıcısına şifre atamak için kullanılır.

`userdell`: Sistemden bir kullanıcı silmek için kullanılır.


## Veri

`less`: Büyük dosyalara bakmak için kullanılır. Dosyanın tamamını ekrana yazdırmaz, daha okunabilir 		    	
hale getirir.

` head`: Bir metin dosyasının ilk satırını görüntülemek için kullanılır. 
> Bu sayı değiştirilebilir  head - n 10 diyerek ilk 10 satırı görüntüleyebilirsiniz.

` tail`:  head komutuna benzerdir. İlk satırlar yerine son satırları gösterir.


## Dosya İzinleri

` chown`: Bir dosyanın sahipliğini belirli bir kullanıcıya transfer etmek için kullanılır.

` chmod`: Dosyaların ve dizinlerin okuma, yazma ve çalıştırma izinlerini değiştirmek için kullanılır.

Bir sistemde temel olarak 3 kullanıcı vardır, bunlar sırasıyla;

-  `owner` dosyanın sahibi

-  `group` bilgisayar üzerinde kayıtlı olan kullanıcılar

-  `other` geri kalan herkes
