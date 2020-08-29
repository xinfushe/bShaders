## Limited Range Tests

bHighL.hlsl: out of range Luma highlighting pixel shader

ffm4b.bat: ffmpeg lossless commands (Windows bat file), incl. changing video bitstream range tag

Avisynth scripts:
* gen_ColorBarsHD.avs 
* LumaHistogram.avs (dynamic display of a video file luma histogram) 
* Create luma_stats.avs: generates a .csv of per frame Luma statistics of a video file
* generate ColorBarsHD test pattern with Avisynth+

ColorBarsHD:
The difference between an expanded and a non expanded limited range is most visible on White.
* avs_rec709_720p-002.png:
![ColorBarsHD rec709](https://github.com/butterw/bShaders/blob/master/test_LimitedRange/avs_rec709_720p-002.png?raw=true)
* avs_pc.709_720p-001.png:
![ColorBarsHD pc.709](https://github.com/butterw/bShaders/blob/master/test_LimitedRange/avs_pc.709_720p-001.png?raw=true)