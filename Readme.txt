更新uboot的操作：
进入当前目录：
./update.sh ./u-boot.bin       //更新uboot.bin
./theone                       //全部打包

备注：
fiptool_arm 工具是ARM架构的服务器下编译的,如果是ARM的编译环境，请用fiptool_arm来更新uboot
fiptool_x86 是在X86的虚拟机下编译的，如果用X86的编译环境，请用fiptool_x86来更新uboot
目前默认的update.sh里面是用fiptool_arm来更新uboot