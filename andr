import tkinter as tk 
from tkinter.scrolledtext import ScrolledText
import os

root = tk.Tk()
cl = '#020f12'
cl2 = '#05d7ff'
cl3 = '#65e7ff'
cl4 = 'BLACK'
root.title('hackmyvm')
root.geometry('750x422')
root.resizable(width=False, height=False)
# -*- coding: utf-8 -*-
# coding=<encoding name>
#!/usr/bin/python







fram = tk.Frame(root, bg=cl, bd=6)


fram.place(relx=0.5, rely=0.25, relwidth=0.7, relheight=0.6, anchor='n')
fram.columnconfigure(0, weight=1)
fram.rowconfigure(1, weight=1)
l = tk.Label(fram, text='enter youer file :', background='springgreen')
l.pack()
en = tk.Entry(fram, background='gray36')
en.pack(pady=10)
l1 = tk.Label(fram, text='enter youer username :', background='springgreen')
l1.pack()
en1 = tk.Entry(fram, background='gray36')
en1.pack(pady=10)


def get_entry_value():
    value = en.get()
    value1 = en1.get()
    with open(value, 'r+') as file:
        for i in file.readlines():
            
            url = 'https://hackmyvm.eu/login/auth.php'
            #sh = input('enter passowrd : ')
            haed = {
                'Accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7',
                'Accept-Encoding': 'gzip, deflate, br',
                'Accept-Language': 'en-US,en;q=0.9,ar;q=0.8',
                'Cache-Control': 'max-age=0',
                'Connection': 'keep-alive',
                'Content-Length': '41',
                'Content-Type': 'application/x-www-form-urlencoded',
                'Cookie': 'PHPSESSID=eoap3itv35mdvnnf22q3qif091',
                'Host': 'hackmyvm.eu',
                'Origin': 'https://hackmyvm.eu',
                'Referer': 'https://hackmyvm.eu/login/',
                'Sec-Fetch-Dest': 'document',
                'Sec-Fetch-Mode': 'navigate',
                'Sec-Fetch-Site': 'same-origin',
                'Sec-Fetch-User': '?1',
                'Upgrade-Insecure-Requests': '1',
                'User-Agent': 'Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36',
                'sec-ch-ua': '"Not_A Brand";v="8", "Chromium";v="120", "Google Chrome";v="120"',
                'sec-ch-ua-mobile': '?0',
                'sec-ch-ua-platform': '"Linux"',
            }


            data = {
                'admin': value1,
                'password_usuario': i.strip(),
                }


            #req = requests.post(url, headers=haed, data=data)

           # if 'Anonymous' in req.text:
           #     print (f'\033[1;32m faund ')
            #    st = ScrolledText(fram, width=50,  height=10, bg=cl2)
            #    st.pack(fill=tk.BOTH, side=tk.LEFT, expand=True)
            #    st.insert(f'end', '[+] username : ' + '[' + value1 + ']' + ' passowerd : ' + '[' + i + ']')
            #    os.system('python vid.py')
            #    break
           # else:
            #    print(f'\033[1;31;40m not   {req.status_code}')
#----------------------------------------------------------------------------|
            



iscdrool = False
def Buttonc():
    global iscdrool
    if not iscdrool:
        get_entry_valuee()
        iscdrool = True
def get_entry_valuee():

    Buttonc()
but = tk.Button(fram, text='set', background=cl2, foreground=cl4, activebackground=cl3, activeforeground=cl4, highlightthickness=2, highlightbackground=cl4,command=get_entry_value)
but.place( x=100, y = 8)

root.mainloop()
