# Ansible-Assessment

Description:
Takes a document of meeting notes (MarkdownMeetingNotes.md) and rewrites them to a google doc with formatting, using Google Colab.

Setup instructions:
Create a folder in your Google Drive called 'Ansible Health'.
Download MarkdownMeetingNotes.md and add it to the folder.
Download the colab file (AnsibleAssesmentColab.ipynb) and open in in Google Colab.


How to run in Colab:
Press the play button next to the first code segment. This will open a window to grant Google Colab to your Google Drive. Follow all the instructions and the window will close itself. Now Google Colab is connected to your Google Drive.

  Required dependencies:
    This project requires docx for python. Clicking the play button on the code segment that says '!pip install python-docx' will install this dependency

Press the play button next to the third and final code segment. This will read the MarkdownMeetingNotes.md, create a Google Doc, write and format the content the Google Doc, and save the document inside the Ansible Health folder as 'MeetingNotes.docx'
