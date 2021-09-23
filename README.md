Extended Sander's script with couple of features:
- Adds thought type as a tag
- Processes Notes.md files
- Adds link notes to ThoughtA's document
- Outputs "delNotes.bat" to delete the notes.html and Notes.md files that were converted
- On Windows I used method 3 as described here to delete empty attachment folders: https://windowsreport.com/remove-empty-folders-windows-10/
- Depending on the characters you've used in thought names, you may need to clean up forbidden characters in the thoughts.json file (like ?:>| etc...). 

------------

# thebrain2markdown
Convert exports from TheBrain to Markdown

1. Export your thoughts from TheBrain to `json`.
2. Edit the script if needed (paths to the json files)


## How to
You will need:
* Python 3+
* html2markdown

1. Export your TheBrain files: File > Export > JSON Files
2. Download the script
3. Create folder `export`
4. Move your export files there
5. Create folder `obsidian`
6. Open Terminal.app and go to the script folder (you can check your current path with `pwd`)
6. Install 'html2markdown' (`pip3 install html2markdown`)
7. Run script `python3 thebrain2markdown.py`
