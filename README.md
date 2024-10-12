# system-monitor

   # 系统监控

   这是一个简单的系统监控工具，可以显示 CPU、内存、磁盘和 GPU 的使用情况。

   ## 功能
   - 实时显示系统资源使用情况
   - 可自定义显示项目
   - 支持系统托盘
   - 自动创建桌面快捷方式

   ## 使用方法
   1. 下载并运行可执行文件
   2. 右键点击窗口可以打开设置菜单
   3. 在系统托盘中可以找到更多选项

   ## 依赖
   - Python 3.6+
   - psutil
   - pynvml
   - pystray
   - Pillow

   ## 构建
   使用 PyInstaller 构建：


   
   pyinstaller --onefile --windowed --add-data "icon.png;." --icon=icon.png system_monitor.py
