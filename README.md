# YouzPress First WordPress Blog Automation

A powerful WordPress blog automation tool that helps you streamline content creation and publishing workflows.

![Blog Automation Logo](icon.ico)

## 🚀 Features

- **Automated WordPress Publishing**: Seamlessly publish content to your WordPress blog
- **Content Management**: Organize and schedule your blog posts efficiently  
- **User-Friendly Interface**: Modern, intuitive design built with Kivy/KivyMD
- **Multi-language Support**: Publish posts in multi language 
- **Secure Authentication**: Safe WordPress credential handling via official REST API
- **Cross-Platform**: Works on Windows for now

## 📋 Requirements

### System Requirements
- **Operating System**: Windows 10/11
- **RAM**: Minimum 4GB
- **Storage**: 30MB free disk space
- **Internet**: Stable internet connection required

### WordPress Requirements
- WordPress 5.6 or higher
- REST API enabled (default in most WordPress installations)
- Valid WordPress user account with publishing permissions

## 📥 Installation

### Windows (Recommended)

1. **Download the Installer**
   - Go to [Releases](https://github.com/youzbotdevs/blog-automation/releases)
   - Download `BlogAutomationInstaller.exe`

2. **Run the Installer**
   - Double-click the downloaded file
   - Follow the installation wizard
   - Accept the terms and conditions
   - Choose installation directory (default recommended)

3. **Launch the Application**
   - Find "Blog Automation" in Start Menu or Desktop
   - Run the application

### Alternative Installation Methods

#### From Source
```bash
# Clone the repository
git clone https://github.com/youzbotdevs/blog-automation.git
cd blog-automation

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
```

#### Portable Version
- Extract the ZIP file to any folder
- Run `main.exe` directly

## 🔧 Configuration

### First-Time Setup

1. **Launch the Application**
2. **WordPress Connection Setup**
   - Enter your WordPress site URL
   - Provide your WordPress username
   - Enter your WordPress application password
   - Test the connection

### Creating Application Password (WordPress)

1. Log into your WordPress dashboard
2. Go to **Users → Profile**
3. Scroll to **Application Passwords**
4. Enter a name: "Blog Automation"
5. Click **Add New Application Password**
6. Copy the generated password
7. Use this password in the Blog Automation app

## 🎯 Usage

### Basic Workflow

1. **Connect to WordPress**
   - Enter your site credentials
   - Verify connection status

2. **Create Content**
   - Write your blog post content
   - Add title and meta information
   - Preview before publishing

3. **Publish**
   - Review your content
   - Click publish to post to WordPress
   - Monitor publishing status


## 🔒 Security & Privacy

### Data Protection
- **Local Storage**: All credentials stored locally on your device
- **No Data Collection**: We don't collect or store your personal information
- **Secure Communication**: All WordPress communication via HTTPS
- **No Third-Party Sharing**: Your data never leaves your control

### Credentials Safety
- Passwords encrypted using industry-standard methods
- Application passwords recommended over main WordPress password
- Secure deletion of stored credentials upon uninstall

## 🛠️ Troubleshooting

### Common Issues

#### Connection Problems
**Issue**: Cannot connect to WordPress site
**Solutions**:
- Verify WordPress URL (include http:// or https://)
- Check internet connection
- Ensure WordPress REST API is enabled
- Verify application password is correct

#### Publishing Failures
**Issue**: Posts fail to publish
**Solutions**:
- Check user permissions in WordPress
- Verify site URL is accessible
- Try regenerating application password
- Check WordPress site status

#### Application Won't Start
**Issue**: Program doesn't launch
**Solutions**:
- Run as administrator (Windows)
- Check antivirus software isn't blocking
- Reinstall the application
- Check system requirements

### Error Codes

| Code | Description | Solution |
|------|-------------|----------|
| 401 | Authentication failed | Check username/password |
| 403 | Permission denied | Verify user permissions |
| 404 | Site not found | Check WordPress URL |
| 500 | Server error | Contact site administrator |

## 🔄 Updates

### Automatic Updates
- The application checks for updates automatically
- Notifications appear when updates are available
- Updates can be installed with one click in about tab

### Manual Updates
- Download latest version from [Releases](https://github.com/youzbotdevs/blog-automation/releases)
- Uninstall old version (optional)
- Install new version

## 🤝 Contributing

We welcome contributions from the community!


## 🆘 Support

### Getting Help
- **Documentation**: Check this README and our [Wiki](https://github.com/youzbotdevs/blog-automation/wiki)
- **Issues**: Report bugs on [GitHub Issues](https://github.com/youzbotdevs/blog-automation/issues)
- **Contact**: Reach out via [YouzBot Contact Page](https://youzbot.com/contact-us/)

### FAQ

**Q: Does it work with WordPress.com?**
A: Yes, but you need a Business plan for REST API access.

**Q: Can I use it with multiple WordPress sites?**
A: Yes, you can configure multiple site connections.

**Q: Is my data safe?**
A: All data is stored locally on your device and transmitted securely.

## 🏢 About YouzBot

Blog Automation is developed by [YouzBot](https://youzbot.com), a company focused on creating productivity tools for content creators and digital marketers.

### Our Mission
To simplify and automate repetitive tasks in content creation, allowing creators to focus on what matters most - creating great content.

### Other Products
- Visit [YouzBot.com](https://youzbot.com) for more automation tools
- Follow us for updates and new releases

## 📊 Statistics

- **Downloads**: 500+ users worldwide
- **GitHub Stars**: ⭐ Star us if you find this useful!
- **Languages**: All languages are supported (The app is in English, but you can post blogs in your desired language)
- **Platforms**: Windows

## 🗺️ Roadmap


### Version History
- **v2.0.0** (Current) - multiple languages support, optimize posted images, change images format to WebP 
- **v1.5.0** - Also add the main image to the post
- **v1.0.0** - Initial release

---

**Made with ❤️ by [YouzBot](https://youzbot.com)**

*If you find this tool helpful, please start sharing the repository with others!*
