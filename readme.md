This repo is to help you easily install mujoco200 and mujoco_py==2.0.2.5 (valid version for windows) in a **windows** conputer


Step 1: move the folder .mujoco to path "C:\Users\ (your_windows_id)"

Step 2: add mujoco to environment path (look up more details)

Step 3: add following lines to the beginning of your code

>import sys 
>
>import os
>
>os.add_dll_directory("C://Users// (your_windows_id)//.mujoco//mujoco200//bin")  
>
>sys.path.append("C://Users// (your_windows_id)//.mujoco//mujoco-py-2.0.2.5")


Maybe you also need to "pip install gym==0.12.1", then run your code


This link is very useful: https://www.cnblogs.com/caiyishuai/p/15978703.html, but no need to do so, if finish the above steps

