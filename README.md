# Automated File Organizer

Automated File Organizer is a Python script designed to automatically organize files within a specified directory based on their types. This project categorizes files such as images, documents, videos, and others into separate folders, improving file management and organization.

## Features

- **File Type Detection:** The script can identify various file types, including images, documents, videos, and others, ensuring accurate categorization.
- **Directory Structure:** Organizes files into structured folders such as Images, Documents, Videos, and Others, maintaining the original file names and hierarchy.
- **Automated Organization:** Utilizes Python's `os` and `shutil` modules to automate the file organization process, enhancing workflow efficiency.
- **Error Handling:** Implements robust error handling mechanisms to address permissions issues and prevent file overwriting, ensuring reliable operation.
- **Optional Features:** Provides user interaction options, preventing accidental overwriting and allowing customization of file categories.

## Usage

To use the Automated File Organizer, follow these steps:

1. Clone the repository:

2. Run the Python script with the following command:

Replace `/path/to/your/directory` with the absolute path of the directory you want to organize.

## Configuration (Optional)

You can customize the script by modifying the configuration variables inside the `organizer.py` file.

- `FILE_TYPES`: Define the file extensions for each category (e.g., `('.jpg', '.jpeg', '.png')` for images).
- `ORGANIZED_FOLDERS`: Define the names of the folders for each file category.
- `CONFIRMATION_REQUIRED`: Set to `True` if you want confirmation before moving each file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the developers of Python and the `os` and `shutil` modules for enabling this project.

Feel free to contribute, report issues, or suggest improvements by creating a pull request. Happy organizing!
