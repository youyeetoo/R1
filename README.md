![image](https://github.com/user-attachments/assets/76bb59ae-d355-41f1-8053-2333af67746a)

# R1
The youyeetoo R1 is an Single Board Computer (SBC) designed by youyeetoo.com for the AIOT (AI of Things) market.Despite its compact size, it boasts powerful features, powered by the flagship RK3588s octa-core 64-bit processor from Rockchip, built on an 8nm process, with a high clock speed of up to 2.4GHz. It integrates an ARM Mali-G610 MP4 GPU and features a built-in NPU (Neural Processing Unit) with 6 TOPS (Trillions of Operations Per Second) of AI computing power. It has faster speeds and lower power consumption, making it suitable for a wide range of AI application scenarios

Although the R1 SBC is only the size of a card (100 * 69.3mm), but it has a rich interfaces, including Gigabit Ethernet, HDMI output (supports 8K), Type-C, M.2 PCIe2.0, dual MIPI cameras and screens, 3 * USB2.0, 1 * USB3.0, 4 * UART serial port, 2 * I2C, GPIO * 7, SPI * 1, ADC * 2, CAN * 1 and other common interfaces for the AIOT(Internet of Things),it support multiple operating systems and can be applied to Edge computing, artificial intelligence, advertising machines, smart homes and other AIoT fields.

The most distinctive feature is that the R1 SBC is also equipped with an NFC(near-field communication) chip. You can use a mobile phone (android/IOS) to touch the motherboard to transfer data to each other, the youyeetoo team provides application example tutorials.

![image](https://github.com/user-attachments/assets/f845aca6-6b93-49f9-a60c-a3cb5d36182d)

>If there are any technical problems, please contact: support@youyeetoo.com
For customization needs, please contact: sales@youyeetoo.com 

## Specification
|Item|descriptions|
|:----------:|:-----------|
|**CPU**|Rockchip RK3588S (8nm LP process)，8-core 64-bit，4xCortex-A76 and 4xCortex-A55，Up to 2.4GHz frequency|
|**GPU**|ARM Mali-G610 MP4  “Odin” GPU <br />● Compatible with  OpenGL ES 1.1/2.0/3.1/3.2 <br />● OpenCL 1.1,1.2,2.0 <br />● Vulkan 1.1，1.2 450 GFLOPS <br />● 3D and 2D graphics engine |
|**NPU**|Built-in AI accelerator NPU with up to 6 TOPS, supports INT4/INT8/INT16 mixed operation<br />(TensorFlow/MXNet/PyTorch/Caffe RKNN support )|
|**RAM**|LPDDR4 4GB/8GB/16GB/32GB <span style="color:#ff0000">(option) </span> |
|**Storage**|● eMMC: 32G/64G/128G/256GB   <span style="color:#ff0000">(option)</span> <br />● M.2 slot(BOTTOM) M-Key  ：<br />&nbsp; @NVMe SSD(PCIe) 2280（ps:The speed is PCIe 2.0）<span style="color:#ff0000">（V2 version supports NVMe 2242 SSD solid-state） </span><br />&nbsp; @SATA3.0 SSD  m.2 2280<span style="color:#ff0000">（V2 version supports NVMe 2242 SSD solid-state） </span><br />● MicroSD (TF) Card Slot|
|**Network**|● Ethernet：RJ45 10/100/1000Mbps Ethernet <br />● Wireless: M.2(E-Key) Socket Expansion Slot <br /> 1. Wi-Fi5+BT5.0 module(RTL8822CE) default driver <br /> 2. WI-FI6+BT5.2 dual-band WiFi+BT module <br />●4G LTE： M.2(M-Key)Socket Expansion Slot<br />(default driver for  EC20/EC25  4G LTE Data) <br />(Need a 4G adapter board)|
|**VPU** <br />（video Codec）|**Video decoding:** <br />● 8K@60fps H.265/H.264/VP9/AVS2 <br /> ● 8K@30fps H.264 AVC/MVC<br />● 4K@60fps AV1 <br />● 1080P@60fps MPEG-2/-1/VC-1/VP8 <br /> **Video encoding:** <br /> ● 8K@30fps  H.265 / H.264 encoding <br />(Up to 32-channel 1080P@30fps decoding + 16-channel 1080P@30fps encoding)|
|**Display**<br />（Multi screen)|● HDMI: 1 x HDMI2.1 (8K@60Hz or 4K@120Hz) <br />● MIPI FPC：2 x MIPI-DSI (DSI0/DSI1  4K@60Hz)<br />default driver the MIPI7LCD (1024 * 600 LCD touch screen) <br />● <span style="color:#ff0000"> DP: 1 x Type C for DP1.4  (8K@30Hz)（V2 version is available, V3 version has been removed）</span>|
|**Camera**|MIPI FPC slots ：2 x MIPI CSI 4 lane (MIPI_CPHY0/MIPI_CPHY1)|
|**USB**|● USB-A ：USB 2.0 * 3  (Limit 500mA)<span style="color:#ff0000">(V2:USB2.0 * 2)</span><br /> ● USB-A ：USB 3.0 * 1  (Limit 1A)<br /><span style="color:#ff0000">(V3:By using the dip switch on the back, you can choose between DEVICE or HOST)</span> <br />● <span style="color:#ff0000">USB-C :  TypeC  * 1（USB3.1 OTG / DP1.4）（Limit 2A）(V2 version is available, V3 version has been removed)</span><br />● USB socket：USB 2.0 * 1（4 pin header: PH-4A 2.0mm ）|
|**Audio Output**|1. 3.5mm audio jack x 1  (with mic)<br />2. HDMI audio output<br />3. 4 pin headerJ368：R/L/GND/MIC  （header：SH1.25mm）<br />(The signal is parallel to the 3.5 audio jack)|
|**Audio Input**|1. 1.Microphone  x1 (On board ) <br /> 2. MIC socket：2pin header for MIC 3.3V（1.25mm SH1.25）<br /> 3. 3.MIC in 3.5mm audio jack|
|**M.2 Socket**|●M.2-1(BOTTOM) 2242 M-key：PCle Gen2.0 lane 2 <br />&nbsp;&nbsp; @support NVME SSD/SATA SSD <br />&nbsp;&nbsp; @support 4G LTE (need M.2 to MiniPCIE adapter board)<br />● M.2-2(TOP)2230 E-key：Support module（WIFI5+BT5.0 / WIFI6+BT5.2）|
|**30PIN Socket**<br />（extending）<br />header：PH2.0mm|●I2C:I2C * 3 (I2C1、I2C3、I2C7) default 3.3V <br />●UART：UART * 3(UART5、UART7、UART9) default 3.3V<br />●CAN：CAN * 1 （need CAN conversion board ）<br />●PWM：PWM * 1(PWM7)<br />●ADC: ADC * 2(ADC3、ADC4)<br />● GPIO:GPIO pin * 7    default 3.3V support 1.8V(need change BIOS)<br />(GPIO1_A7/GPIO1_A4/GPIO1_D5/GPIO2_A6/GPIO1_B1/GPIO0_B0/GPIO0_A0)<br />●VCC:VCC * 2(VCC3v3、VCC5v)<br />●SPI(pin:14,16,19,21,23) Reuses I2C7 and UART9|
|**Debug port**|Debug UART * 1 （UART2  3P  SH1.25）|
|**LED light**|LED * 2 red/green，4 Pin out socket ,parallel，（Programmable）|
|**Button**|key * 4  :Boot/Reset /Recovery /Power|
|**Power**|● DC jeck : 12V（5.5x2.1mm，12V3A） <br />● Pin socket  red: 2Pin  2.54 pitch|
|**RTC**|RTC Button battery socket ：2Pin 1.25mm  SH1.25|
|**Size**|100 x 69.3mm|
|**NFC**|NFC near field communication, Connect an external antenna, you can Data transfer with mobile phone,  android/iOS support <br />youyeetoo.com provides examples tutorials and API |
|**HDMI IN**|Maximum Support 4K@60Hz (YUV420  )  <span style="color:#ff0000"> (option) </span> <br />（Adapter board to the MIPI-CSI port：  RK628D ）|
|**OS Support**|● Android 13(kernel 5.10) <br />● Debian 11(kernel 5.10) <br /> ● Ubuntu 22.04(kernel 5.10) <br /> ● Linux Buildroot(kernel 5.10) <br />●  OpenHarmony(4.0) <br />|

# Getting Started Tutorial

- [Introduction to peripherals (to be written...) *Shipping list* *Package* *Schematic diagram* *Interface properties* *Seat specifications* *Pin reuse table* *Development board weight and size*](http://wiki.youyeetoo.com/en/r1/hardware)
- [Serial port debugging (to be written...) *Hardware connection* *Serial port parameters* *Windows serial port debugging* *Ubuntu Virtual Machine Serial Port Debugging*](http://wiki.youyeetoo.com/en/r1/uartdebug)
- [Adb debugging (to be written...)*Hardware connection* *Windows adb debugging* *Ubuntu Virtual Machine adb Debugging*](http://wiki.youyeetoo.com/en/r1/adbdebug)
{.links-list}

## Interface Definition
- 30PIN extension pin

![image](https://github.com/user-attachments/assets/b849ed02-3703-44ff-90d7-a20f92a97d6c)

|Num| Pin | Pin type | Default Pin type | Default IO Pull | Pull Resistor,Normal |Voltage/V|Support Drive strength|Default IO Driver strength| Func1 | Func2 | Func3 | Func4| Func5 | Func6 |Func7 | Func8 | Func9 | Func10 |
|:-----------|:-----------|:-----------|:---|:---|:--- |:--- |:--- |:--- |:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|1| DC_5V | |  | | |5V |  | | | | |  |  | | | | | |
|2| VCC3V3_SYS | | | | | 3.3V |  | | | | |  |  | | | | |
|3| GND | | | | | |  | | | | |  |  | | | | |
|4| GND | | | | | |  | | | | |  |  | | | | |
|5| I2C3_SCL_M2 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA|GPIO4_A4 | CIF_D4 |BT1120_D4| | |I2C3_SCL_M2 |UART0_RX_M2  |  SPI2_MISO_M1| | |
|6| UART5_RX_M1/CAN2_TX_M0 |I/O| I | UP | 1.8V:  Pull-up/down:10k-50k3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO3_C5 | CIF_D9 | | |SPI3_CS1_M3 | FSPI_CS1N_M2 | UART5_RX_M1 |  | CAN2_TX_M0 | |
|7| I2C3_SDA_M2 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO4_A5 | CIF_D5 | BT1120_D5 || I2S1_SDI0_M0 | I2C3_SDA_M2 | UART3_TX_M2 | SPI2_MOSI_M1 | | |
|8| UART5_TX_M1/CAN2_RX_M0 |I/O| I | UP | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO3_C4 | CIF_D8 ||| SPI3_CS0_M3 | FSPI_CS0N_M2 | UART5_TX_M1 | CAN2_RX_M0 | | |
|9|GPIO1_A6 |I/O|I|DOWN| 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA|GPIO1_A6|  |  | |SPI2_CLK_M0| | |  |  | | |
|10| UART7_TX_M1 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO3_C0 | GMAC1_PPSTRIG | | | SPI1_MISO_M1 | I2C3_SDA_M1 | UART7_TX_M1 | | | |
|11| GPIO1_A4 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO1_A4 |  | | | | SPI2_MISO_M0 |  |  | | |
|12| UART7_RX_M1 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO3_C1 | GMAC1_PPSCLK | | | SPI1_CLK_M1 | | UART7_RX_M1 |  | | |
|13| GPIO1_A7 |I/O| I | UP | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO1_A7 |  | PDM1_SDI0_M1 | | PCIE20X1_1_PERSTN_M2 | SPI2_CS0_M0 | PWM3_IR_M3 |  | | |
|14| UART9_RX_M2 |I/O| I | DOWN |1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k|3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO3_D4 | MCU_JTAG_TCK_M1 | HDMI_TX0_HPD_M1 || SPI0_CS0_M3 | | UART9_RX_M2 |  | | |
|15| GPIO1_B1_d |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k|3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA | GPIO1_B1 |  | DM1_SDI2_M1 || | SPI0_MISO_M2 |  |  |||
|16| UART9_TX_M2 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k|3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA | GPIO3_D5 | MCU_JTAG_TMS_M1 ||| SPI0_CS1_M3 | | UART9_TX_M2 |  |||
|17| GPIO1_D5 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k |1.8V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO1_D5 |  || PDM0_SDI0_M0 | | |  | SPI1_CS1_M2  |||
|18| PWM7 |I/O| I | DOWN |1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k|1.8V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO0_D0 | PWM7_IR_M0 | I2C6_SCL_M0 | SPI3_MISO_M2 | | I2S1_SDI3_M1 | PDM0_SDI1_M1 |  | UART1_CTSN_M2||
|19| GPIO3_D1 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO3_D1 | CIF_D13 ||| SPI0_MISO_M3 | | UART4_TX_M1 | PCIE20X1_2_PERSTN_M0 |||
|20| CAN_RX_M1 |I/O| I | UP | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO0_D4 | PWM3_IR_M0 | I2C1_SCL_M2 | SPI3_CS0_M2 | | I2S1_SDO2_M1 | PDM0_SDI2_M1 | CAN2_RX_M1 | SATA_CPDET | HDMI_TX0_SDA_M1|
|21| I2C7_SCL_M2 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO3_D2 | CIF_D14 ||  | SPI0_MOSI_M3 | I2C7_SCL_M2 | UART9_RTSN_M2 |  |||
|22| CAN_TX_M1 |I/O| I | UP | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO0_D5 | CPU_BIG1_AVS | I2C1_SDA_M2 | SPI3_CS1_M2 | | I2S1_SDO3_M1 |  | CAN2_TX_M1 | SATA_MP_SWITCH | HDMI_TX0_SCL_M1 |
|23| I2C7_SDA_M2 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |3.3V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA|GPIO3_D3 | CIF_D15 ||| SPI0_CLK_M3 | I2C7_SDA_M2 | UART9_CTSN_M2 |  | PWM10_M2 ||
|24| ADC3 |||||1.8V|  |  |SARADC_IN3|| | |  |  ||| ||
|25| GPIO0_A0 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k 3.3V:  Pull-up/down:10k-100k |1.8V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO0_A0 | REFCLK_OUT ||| | |  |  |||
|26| ADC4 |||||1.8V|  |  |SARADC_IN4|| | |  |  |||||
|27| I2C1_SDA_M4 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k |1.8V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO1_D3 | I2S0_SDI1 || PDM0_SDI3_M0 | I2C1_SDA_M4 | PWM1_M1 | UART4_RX_M0 | SPI1_CS0_M2 |||
|28| I2C1_SCL_M4 |I/O| I | DOWN | 1.8V:  Pull-up/down:10k-50k |1.8V|3mA,4.5mA,6mA,7.5mA,9mA,12mA|7.5mA| GPIO1_D2 | I2S0_SDO3 | I2S0_SDI2 | PDM0_SDI2_M0 | I2C1_SCL_M4 | PWM0_M1 | UART4_TX_M0 | SPI1_CLK_M2 |||
|29| GND |||||  |  ||| | |  |  |||||
|30| GND |||||  |  ||| | |  |  |||||


# R1 schematic and R1 2D image
- schematic:
  [Official Download 
  *http://dd.youyeetoo.cn:5000/sharing/ZGvrtmVJ0*](http://dd.youyeetoo.cn:5000/sharing/ZGvrtmVJ0)
  [Google Download  
  *https://drive.google.com/file/d/15rnMDm7OGMbaJnoJie1Z61bm9hztCIfo/view?usp=sharing*](https://drive.google.com/file/d/15rnMDm7OGMbaJnoJie1Z61bm9hztCIfo/view?usp=sharing)
  
{.links-list}

- 2D:
  [Official Download 
  *http://dd.youyeetoo.cn:5000/sharing/3W8rVap8y*](http://dd.youyeetoo.cn:5000/sharing/3W8rVap8y)
  [Google Download  
  *https://drive.google.com/drive/folders/1odofFBLDzwvVfBMcGtsXIp8b1CRU_kbl?usp=drive_link*](https://drive.google.com/drive/folders/1odofFBLDzwvVfBMcGtsXIp8b1CRU_kbl?usp=drive_link)
  
{.links-list}

# parts

- [Parts list (to be written...) *MIPI7LCD* *csi camera* *...*](http://wiki.youyeetoo.com/en/r1/accessory)
{.links-list}

# Firmware burning and source code compilation<span id="r1-burn"></span>
This chapter introduces the methods of burning the system and source code compilation. If you encounter issues such as inability to recognize the device or enter burning mode when burning the system, please click<a href="#r1-problem">frequently asked question</a>Find a solution.

> Note: R1 boards purchased before April 1, 2024（There is no QR code on the back of the board）need to be updated using the update configuration tool below, otherwise the burned firmware will not start normally.
{.is-warning}
- [Updated configuration tool *Compatible with older versions of the board*](https://wiki.youyeetoo.com/en/r1/r1AfterSalesToolsen)
- [Burn to EMMC *Android system* *Debian system* *Ubuntu system*](http://wiki.youyeetoo.com/en/r1/burnemmc)
- [Burn to tf card *Android system* *Debian system* *Ubuntu system*](http://wiki.youyeetoo.com/en/r1/burntf)
- [Android source code compilation *Compile complete firmware* *Step-by-step compilation*](http://wiki.youyeetoo.com/en/r1/Acompile)
- [Debian source code compilation *Compile complete firmware* *Step-by-step compilation*](http://wiki.youyeetoo.com/en/r1/Dcompile)
- [Ubuntu source code compilation *Compile complete firmware* *Step-by-step compilation*](https://wiki.youyeetoo.com/en/r1/Ucompile)
- [Image Repack](https://wiki.youyeetoo.com/en/r1/ImgRepack)
- [3rd System *Armbian* *and so on*](https://wiki.youyeetoo.com/en/r1/3rdSystem)
{.links-list}

# OpenHarmony System User Manual
- [Monitor *HDMI Display* *7-inch MIPI screen*](https://wiki.youyeetoo.com/en/r1/OUHDMI)
- [OUBUS *GPIO* *USB* *UART* *I2C* *SPI* *PWM* *CAN* *ADC*](https://wiki.youyeetoo.com/en/r1/OUBUS)
- [Network *Ethernet* *WIFI/BT* *4G EC20*](https://wiki.youyeetoo.com/en/r1/OUNET)
- [Camera *Camera*](https://wiki.youyeetoo.com/en/r1/OUCAMERA)
- [Storage *SD Card* *NVME SSD* *SATA SSD*](https://wiki.youyeetoo.com/en/r1/OUSTORAGE)
- [Audio *Headphones* *MIC*](https://wiki.youyeetoo.com/en/r1/OUAUDIO)
- [MISC Devices *RTC* *FAN* *codec*](https://wiki.youyeetoo.com/en/r1/OUMISC)
{.links-list}


# Debian System User Manual

- [Ethernet Configuration](http://wiki.youyeetoo.com/en/r1/DUethernet)
- [TF card read and write speed test](http://wiki.youyeetoo.com/en/r1/DUtf)
- [Codec usage](http://wiki.youyeetoo.com/en/r1/DUcodec)
- [RTC configuration](http://wiki.youyeetoo.com/en/r1/DUrtc)
- [WiFi configuration](http://wiki.youyeetoo.com/en/r1/DUwifi)
- [HDMI settings](http://wiki.youyeetoo.com/en/r1/DUhdmi)
- [CSI usage](http://wiki.youyeetoo.com/en/r1/DUcsi)
- [I2c usage](http://wiki.youyeetoo.com/en/r1/DUi2c)
- [gpio usage](http://wiki.youyeetoo.com/en/r1/DUgpio)
- [UART usage](http://wiki.youyeetoo.com/en/r1/DUuart)
- [PWM usage](http://wiki.youyeetoo.com/en/r1/DUpwm)
- [Can usage](http://wiki.youyeetoo.com/en/r1/DUcan)
- [ADC usage](http://wiki.youyeetoo.com/en/r1/DUadc)
- [USB usage](http://wiki.youyeetoo.com/en/r1/DUusb)
- [SPI usage](http://wiki.youyeetoo.com/en/r1/DUspi)
- [dp usage (to be written...)](http://wiki.youyeetoo.com/en/r1/DUdp)
- [NFC usage](http://wiki.youyeetoo.com/en/r1/DUnfc)
- [Docker usage](http://wiki.youyeetoo.com/en/r1/DUdocker)
- [HDMI IN](http://wiki.youyeetoo.com/en/r1/DUhdmiin)
- [Screen time setting](https://wiki.youyeetoo.com/en/r1/DUdisplay)
{.links-list}

# Android System User Manual

- [Ethernet Configuration](http://wiki.youyeetoo.com/en/r1/AUethernet)
- [TF card read and write speed test](http://wiki.youyeetoo.com/en/r1/AUtf)
- [Codec usage](http://wiki.youyeetoo.com/en/r1/AUcodec)
- [RTC configuration ](http://wiki.youyeetoo.com/en/r1/AUrtc)
- [WiFi configuration ](http://wiki.youyeetoo.com/en/r1/AUwifi)
- [HDMI settings](http://wiki.youyeetoo.com/en/r1/AUhdmi)
- [CSI usage ](http://wiki.youyeetoo.com/en/r1/AUcsi)
- [I2c usage](http://wiki.youyeetoo.com/en/r1/AUi2c)
- [gpio usage](http://wiki.youyeetoo.com/en/r1/AUgpio)
- [UART usage ](http://wiki.youyeetoo.com/en/r1/AUuart)
- [PWM usage ](http://wiki.youyeetoo.com/en/r1/AUpwm)
- [Can usage ](http://wiki.youyeetoo.com/en/r1/AUcan)
- [ADC usage ](http://wiki.youyeetoo.com/en/r1/AUadc)
- [USB usage (to be written...)](http://wiki.youyeetoo.com/en/r1/AUusb)
- [SPI usage (to be written...)](http://wiki.youyeetoo.com/en/r1/AUspi)
- [dp usage (to be written...)](http://wiki.youyeetoo.com/en/r1/AUdp)
- [NFC usage](http://wiki.youyeetoo.com/en/r1/AUnfc)
- [HDMI IN ](http://wiki.youyeetoo.com/en/r1/AUhdmiin)
{.links-list}

# Ubuntu System User Manual

- [Ethernet Configuration](https://wiki.youyeetoo.com/en/r1/UUethernet)
- [tf card reading and writing speed test](https://wiki.youyeetoo.com/en/r1/UUtf)
- [Use of headphones](https://wiki.youyeetoo.com/en/r1/UUcodec)
- [RTC Configuration](https://wiki.youyeetoo.com/en/r1/UUrtc)
- [wifi configuration](https://wiki.youyeetoo.com/en/r1/UUwifi)
- [HDMI Settings](https://wiki.youyeetoo.com/en/r1/UUhdmi)
- [Use of camera](https://wiki.youyeetoo.com/en/r1/UUcsi)
- [I2c use](https://wiki.youyeetoo.com/en/r1/UUi2c)
- [Usage of gpio](https://wiki.youyeetoo.com/en/r1/UUgpio)
- [Usage of uart](https://wiki.youyeetoo.com/en/r1/UUuart)
- [pwm use](https://wiki.youyeetoo.com/en/r1/UUpwm)
- [can use](https://wiki.youyeetoo.com/en/r1/UUcan)
- [Use of adc](https://wiki.youyeetoo.com/en/r1/UUadc)
- [usb use](https://wiki.youyeetoo.com/en/r1/UUusb)
- [spi use](https://wiki.youyeetoo.com/en/r1/UUspi)
- [nfc use](https://wiki.youyeetoo.com/en/r1/UUnfc)
- [docker use](https://wiki.youyeetoo.com/en/r1/UUdockerfix)
- [HDMI IN (to MIPI-CSI) ](https://wiki.youyeetoo.com/en/r1/UUhdmiin)
{.links-list}

# Windows System User Manual

- [Running ARM Windows 11 System on R1 Development Board](https://wiki.youyeetoo.com/en/r1/WindowOnArm)
{.links-list}

# Drive configuration

For some pin reuse and functional conflicts, it is necessary to modify the device tree. After modifying the device tree, go to<a href="#r1-burn">Firmware burning and source code compilation</a>Perform source code burning in this chapter, followed by firmware burning.

- [DSI1, DSI0 on/off ](http://wiki.youyeetoo.com/en/r1/Kdsi)
- [SPI (pins: 14,16,19,21,23) and I2c7, uart9 switching](http://wiki.youyeetoo.com/en/r1/Kspi)
{.links-list}
<!-- 
- [GPIO pin reuse (to be written...)](http://wiki.youyeetoo.com/en/r1/Kgpio)
- [Power on or press to start settings (to be written...)](http://wiki.youyeetoo.com/en/r1/Kpower)
-->


# Debian Programming Guide

- [Camera programming](http://wiki.youyeetoo.com/en/r1/DCcamera)
- [i2c programming](http://wiki.youyeetoo.com/en/r1/DCi2c)
- [GPIO programming](http://wiki.youyeetoo.com/en/r1/DCgpio)
- [uart programming](http://wiki.youyeetoo.com/en/r1/DCuart)
- [PWM programming](http://wiki.youyeetoo.com/en/r1/DCpwm)
- [Can programming](http://wiki.youyeetoo.com/en/r1/DCcan)
- [ADC programming](http://wiki.youyeetoo.com/en/r1/DCadc)
- [SPI programming](http://wiki.youyeetoo.com/en/r1/DCspi)
- [NFC programming](http://wiki.youyeetoo.com/en/r1/DCnfc)
- [qt programming ](http://wiki.youyeetoo.com/en/r1/DCqt)
- [OpenCV programming](http://wiki.youyeetoo.com/en/r1/DCopencv)
- [rga programming](http://wiki.youyeetoo.com/en/r1/DCrga)
- [MPP programming](http://wiki.youyeetoo.com/en/r1/DCmpp)
- [NPU programming](http://wiki.youyeetoo.com/en/r1/DCnpu)
{.links-list}

All of the above chapters require the use of a cross-compiler, and the chapters from i2c programming to spi programming require the use of a static library and header files. The download links for these, and how to use them, can be found in the following sections

- [Cross-compiler and static library download links](http://wiki.youyeetoo.com/en/r1/Dcomplier)
{.links-list}

# Android Programming Guide

This chapter uses Android stdio software for programming and requires a Java programming foundation. If you do not have a foundation in Java, please learn Java related knowledge on your own. The following routines are written based on the system app.

- [Creating a system app ](http://wiki.youyeetoo.com/en/r1/ACapp)
- [Camera programming ](http://wiki.youyeetoo.com/en/r1/ACcamera)
- [i2c programming ](http://wiki.youyeetoo.com/en/r1/ACi2c)
- [GPIO programming ](http://wiki.youyeetoo.com/en/r1/ACgpio)
- [uart programming](http://wiki.youyeetoo.com/en/r1/ACuart)
- [PWM programming ](http://wiki.youyeetoo.com/en/r1/ACpwm)
- [Can programming](http://wiki.youyeetoo.com/en/r1/ACcan)
- [ADC programming ](http://wiki.youyeetoo.com/en/r1/ACadc)
- [SPI programming ](http://wiki.youyeetoo.com/en/r1/ACspi)
- [NFC programming](http://wiki.youyeetoo.com/en/r1/ACnfc)
- [OpenCV programming ](http://wiki.youyeetoo.com/en/r1/ACopencv)
{.links-list}
<!--
- [rga programming (to be written...)](http://wiki.youyeetoo.com/en/r1/ACrga)
- [MPP programming (to be written...)](http://wiki.youyeetoo.com/en/r1/ACmpp)
- [NPU programming (to be written...)](http://wiki.youyeetoo.com/en/r1/ACnpu)
-->

# Ubuntu Programming Guide
- [Camera Programming](https://wiki.youyeetoo.com/en/r1/UCcamera)
- [I2C Programming](https://wiki.youyeetoo.com/en/r1/UCi2c)
- [GPIO Programming](https://wiki.youyeetoo.com/en/r1/UCgpio)
- [UART Programming](https://wiki.youyeetoo.com/en/r1/UCuart)
- [PWM Programming](https://wiki.youyeetoo.com/en/r1/UCpwm)
- [CAN Programming](https://wiki.youyeetoo.com/en/r1/UCcan)
- [ADC Programming](https://wiki.youyeetoo.com/en/r1/UCadc)
- [SPI Programming](https://wiki.youyeetoo.com/en/r1/UCspi)
- [nfc programming (to be written)](https://wiki.youyeetoo.com/en/r1/UCnfcFix)
- [qt programming (to be written)](https://wiki.youyeetoo.com/en/r1/UCqt)
- [opencv programming](https://wiki.youyeetoo.com/en/r1/UCopencv)
- [rga programming](https://wiki.youyeetoo.com/en/r1/UCrga)
- [mpp programming](https://wiki.youyeetoo.com/en/r1/UCmpp)
- [NPU programming](https://wiki.youyeetoo.com/en/r1/UCnpu)
{.links-list}

All the above chapters require a cross compiler, and the chapters from i2c programming to spi programming require a static library and header files. The download links and usage instructions for these contents can be found in the following sections

- [Cross compiler and static library download links](https://wiki.youyeetoo.com/en/r1/Ucomplier)
{.links-list}

# Ubuntu
After the R1 Linux Desktop system is started, it automatically logs in to the user youyeetoo.
If the debugging serial port is connected, the serial port terminal automatically logs in as the root user.
**user:** youyeetoo **password：** 123456
root ：default no root password，
you can set password yourself via: sudo passwd root

- [Updated configuration tool *Compatible with older versions of the board*](https://wiki.youyeetoo.com/en/r1/r1AfterSalesToolsen)
- [Ubuntu source code compilation *Compile complete firmware* *Step-by-step compilation*](https://wiki.youyeetoo.com/en/r1/Ucompile)

# FAQ <span id="r1-problem"></span>
- [Unable to burn system (pending writing...)](http://wiki.youyeetoo.com/en/r1/problem1)
- [tf card cannot start (pending writing...)](http://wiki.youyeetoo.com/en/r1/problem2)
- [Unable to recognize adb (pending writing...)](http://wiki.youyeetoo.com/en/r1/problem3)
- [NFC Question (To be Written...)](http://wiki.youyeetoo.com/en/r1/problem4)
- [Configuration of power on self start and button start (to be written...)](http://wiki.youyeetoo.com/en/r1/problem5)
{.links-list}

# Patch Release
- [Patch *Solve the problem of emmc abnormal power failure and disk abnormality* *PCLE Patch*](https://wiki.youyeetoo.com/en/r1/Patch-Release)
{.links-list}

