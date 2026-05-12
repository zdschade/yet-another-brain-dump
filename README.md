# Yet-Another-Brain-Dump

Forked from [Brain Dump](https://github.com/adrienthiery/pebble-watchface-agent-skill).

# My changes

### Local notes not working

Local notes worked if you had nothing enabled, but if you enabled *any* option in the settings, it would always route there. This adds a checkbox in the settings to allow local saves and adds some keywords to that effect.

**Keywords (WIP):** 
['note', 'note to self', 'notes', 'reminders', 'reminder', 'local', 'local note', 'local reminder']

### Removal of Claude skill in root path

adrienthiery used the pebble-watchface-agent-skill for claude in this apps creation. However, instead of putting the skill in *.claude*, they left many of the files in the root of the repo. I have removed the skill outright, but it can be added back in as long as it is put in *.claude*.

In the future, I would encourage you clone the claude skill into an alredy existing folder you intend to use for a project, not create your project within the claude skill.

> [!IMPORTANT]
> I have no intention of publishing or sharing this fork. If adrienthiery would like to incorporate my changes back into the main project to fix the live version, I enourage them to do so.
