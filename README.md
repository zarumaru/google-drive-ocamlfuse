## google-drive-ocamlfuse

### FUSE filesystem for Google Drive

`google-drive-ocamlfuse` is a FUSE-based file system backed by Google Drive, written in OCaml.
It lets you mount your Google Drive on Linux. The project is hosted on [github](https://github.com/astrada/google-drive-ocamlfuse/),
where you can find the latest development version. Project's documetation is hosted [here](https://github.com/astrada/google-drive-ocamlfuse/wiki).
There are Ubuntu packages in this [PPA](https://launchpad.net/~alessandro-strada/+archive/ubuntu/ppa).

### Features

* Full read/write access to ordinary files and folders
* Read-only access to Google Docs, Sheets, and Slides (exported to
  configurable formats)
* Multiple account support
* Duplicate file handling
* Access to trash (`.Trash` directory)
* Unix permissions and ownership
* Symbolic links
* Read-ahead buffers when streaming
