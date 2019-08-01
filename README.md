# iStats - iMessage Statistics

Team Members: 
Bryce Brooks, Wyatt Harrell, Myra Mullis, John Rawley

Objective: 
provide analytics on IMessages from IMessage app on MacBook. 

About iStats:
iStats was created as a program to output statistics on sent iMessages. 
iStats was written in Python and makes use of the chat.db file generated by Mac devices. 
The front end was created using Flask, HTML, and JavaScript to output statistics in a readable format. 

Features:
Top 10 words, characters, and emojis, displayed with graphs; maximum, minimum, and average character count; 
most texted contact; find a phrase; activity by date

Division of Work:
John - File read in, storing in pandas dataframe, and desired functions; 
Data concerning date and time; gather.py
Bryce - Top 10 words, top 10 characters, top 10 emojis; analysis.py
Myra - Maximum, minimum, average character count, most texted contact, find a 
phrase; analysis.py
Wyatt - GUI, graphics

How to run:
  - Move chat.db file to desktop
  - Change path variable in gather.py line 11
  - use command 'python iStats.py' from project folder

Python Libraries:
- pandas			
- sqlite3			
- time
- datetime
- statistics 
- emojis

Other resources:
- Python documentation and documentation for each of the libraries used

