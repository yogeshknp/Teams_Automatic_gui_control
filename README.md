# Teams_Automatic_gui_control

## Installation and setup
You should have Python3 and Jupyter Notebook installed in your system 

Install these libraries from an administrator terminal (windows):

pip install pywin32
pip install keyboard
pip install pyautogui
pip install opencv-python

Download the [file/folder](https://github.com/yogeshknp/Teams_Automatic_gui_control/archive/main.zip) open the file named 'teams_script_for_automatically_attending_Lecture.ipynb' on jupyter and edit 'my_courses' dictionary and 'course_timetable' dictionary according to you.
**make sure that the course number for example EE204 should be exactly present in your teams group name**

An Example:

my_courses={'EE442':'Microwave Engineering Lab',</br>
'EE499':'BTP',<\br>
'EE626':'Pattern Recognition and Machine Learning',</br>
'HS-401':'Management of Organizational Behaviour',</br>
'EE674':'Sychrophasor Technology',</br>
'EE621':'Computer Vision',</br>
'EE 661':'Power Electronics for Renewable Energy Systems'}

course_timetable = {'mon':['EE422,11:00,60','EE626,12:01,60','EE621,14:02,60','EE674,16:03,60'],</br>
                    'tue':['EE626,12:00,60','EE621,14:01,60','EE 661,15:02,60','EE674,16:03,60'],</br>
                    'wed':['HS-401,12:00,60','EE 661,13:01,60','EE621,14:02,60'],</br>
                    'thu':['HS-401,12:00,60','EE 661,13:01,60','HS401,14:02,60'],</br>
                    'fri':['EE626,11:00,60','HS-401,12:01,60','EE674,15:02,60']}</br>
                    
For example: 'HS-401' is contained in my team group name as Grp_**HS-401**:Management of Organizational Behaviour.
The key in my_courses and course_timetable must match.

'EE422,11:00,60' the format for this is <course_code>,hrs:min (time in 24 hr clock),(duration in minutes)
 make sure in a single the lecture time is in order ie.,lecture at 11:00 comes before 13:00

## How to use
after all the basic configuration simply run all the blocks and relax!

