### Install PyTorch and dependencies

For Installation of PyTorch see [official website](https://pytorch.org/).

You also need `nltk`:
 ```console
pip install nltk
 ```

If you get an error during the first run, you also need to install `nltk.tokenize.punkt`:
Run this once in your terminal:
 ```console
$ python
>>> import nltk
>>> nltk.download('punkt')
```

## Usage
Run
```console
python train.py
```
This will dump `data.pth` file. And then run
```console
python chat.py
```
## Usable Words

"Hi","Hey","Apa kabar?","Apakah ada orang?","Hello","Selamat siang"
"Bye", "Sampai jumpa lagi", "Selamat tinggal"
"Terimakasih", "Sangat membantu", "Terima kasih banyak!"
"Item apa yang Anda miliki?","Jenis barang apa yang ada disana?","Apa yang kamu jual?"
"Apakah kamu mengambil kartu kredit?","Apakah Anda menerima Mastercard?","Bisakah saya membayar dengan Paypal?","Apakah Anda hanya uang tunai?"
"Berapa lama waktu pengiriman?","Kapan saya menerima pengiriman saya?"
"Ceritakan lelucon!","Katakan padaku sesuatu yang lucu!","Apakah Anda tahu lelucon?"
"Siapa kamu?",S"Kuliah dimana?"

# simplebot
