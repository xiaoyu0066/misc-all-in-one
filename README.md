# misc-all-in-one
本脚本为杂项文件隐写一把梭脚本，建议在kali等linux系统使用，可以大大提高比赛杂项做题速度。
使用此脚本前应该安装以下工具：
## exiftool 查看exif信息
`apt-get install exiftool`
## strings
这个命令kali默认自带
## binwalk
```git clone https://github.com/devttys0/binwalk.git
cd binwalk
python3 setup.py install
```
## foremost
`apt-get install foremost`
## zsteg
```git clone https://github.com/zed-0xff/zsteg
cd zsteg/
gem install zsteg
```
## pngcheck
`apt-get install pngcheck`
## outguess
```
git clone https://github.com/crorvick/outguess
cd outguess
./configure && make && make install
```
## F5-steganography-master
`git clone https://github.com/matthewgao/F5-steganography`

##todo:
增加压缩包处理
根据不同文件类型进行分析
