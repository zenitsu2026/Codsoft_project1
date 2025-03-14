# Alarm Clock App

## Overview
The **Alarm Clock App** is a simple yet efficient Android application that allows users to set, edit, and delete alarms. The app provides a user-friendly interface with intuitive controls for managing alarms. Built using **Java** in **Android Studio**, this app ensures smooth functionality with minimal battery consumption.

## Features
- Set multiple alarms
- Edit and delete alarms
- Snooze functionality
- Vibration and sound alerts
- User-friendly interface
- Background service to trigger alarms
- Customizable alarm tones

## Technologies Used
- **Language:** Java
- **IDE:** Android Studio
- **Database:** SQLite (for storing alarm details)
- **UI Design:** XML
- **Notifications:** Android Notification Manager
- **Background Service:** AlarmManager & BroadcastReceiver

## Installation
1. Clone the repository or download the source code.
   ```sh
   git clone https://github.com/your-repo/alarm-clock-app.git
   ```
2. Open **Android Studio** and select **Open an existing project**.
3. Navigate to the project directory and open it.
4. Ensure that the necessary dependencies are installed in **Gradle**.
5. Run the application on an emulator or a physical device.

## How to Use
1. Launch the app.
2. Tap on the **Add Alarm** button.
3. Set the desired time and customize alarm settings.
4. Save the alarm, and it will appear in the alarm list.
5. When the alarm goes off, you can **dismiss** or **snooze** it.
6. Edit or delete alarms from the alarm list as needed.

## Permissions Required
- **WAKE_LOCK**: To wake up the device for alarms.
- **RECEIVE_BOOT_COMPLETED**: To reset alarms after a device reboot.
- **FOREGROUND_SERVICE**: For running alarm services in the background.

## Contributing
If you would like to contribute to this project:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Submit a pull request.

## License
This project is licensed under the **MIT License**.

## Contact
For any queries or suggestions, contact us at **ranvverpaul1@gmail.com**.

