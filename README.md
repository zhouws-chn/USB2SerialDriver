# USB2SerialDriver
Include CP210x, CH341, PL2303, FT2232 chip driver on Windows, macOS, Linux and Android.  

Always some people get their usb2serial product work well on their computer but meet problem on other pople's computer. They use their product in office, the network is linked, and maybe Win10 will install driver automatic, then many people don't know their product need driver.

You can download the Respositories to your computer, in order to demonstration your usb2serial product on other people's computer without network.




在ubuntu上电自动加载驱动模块

步骤如下

1. depmod -a

2. 在/etc/modules加入cp210x

3. 拷贝cp210x.ko到/lib/modules/.../kernel/drivers/usb/serial
