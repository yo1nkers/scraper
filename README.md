# scraper
A small script written in tandem with Claude 3 Opus to steal namefg images from 4chan. Claude was able to improve this idea into something legible.

This will download images across most 18+ boards on 4chan for images which are AI generated. The purpose of this is nothing more than a proof of concept for users who want to organize the generations of namefags on the AI generals and threads.

1. Search "cmd" in Windows or do Win+R and enter in "cmd"
2. Run "pip install" for each of the following;
- pip install sys
- pip install requests
- pip install os
- pip install re
- pip install time
- pip install logging
3. Close cmd and edit "script.py" in notepad
4. Scroll down to line 15 and edit the names within the quotation marks to your liking
- There is a name blacklist, in case someone is using a similar name, or if you don't want to download their images when using "search all names"
5. Start "run.bat" and go through the questions
- If you answer "yes" to search all names, it will ignore the names you have entered and download all names
- If you answer "yes" to download anon images, it will download images from also Anonymous users
6. Enter search terms for your search.
- You can split up searches by using "|". For example, if you want to search for something that's not in the AI threads, like YLYL, you could search "degenerated|ylyl", and it will search for them.
- Additionally, you can use "-" before a term if you want to exclude it from the search. An example is below.
- You can use "srch.txt" to automatically search for ALL possible AI threads across 4chan

srch.txt:
```degenerated|sdg|hdg|slop|ddg|asdg|-blacked|-gdg|-futa|-giant|-draw|-non-ai|-Sdbbw|-Dall-e|-blueberry|-Domestication|-swallowed```
