#  <p align=center> <b>Hello, guest!</b>     :raising_hand: </p> 
## <p align=center> Thanks for your interest :thumbsup:     </p>
---


- Hello, I'm Sergey.

- I am interested in working with embedded systems based on ARM-Cortex (for example: STMicroelectronics microcontrollers),
in addition, since childhood, I was really interested in electronics. I designed and assembled simple electronic devices,
but I didn't have enough tools and sources of components (few electronic stores). First of all, in my environment there
was no one who would be interested in this, like me. Now I am studying programming in C, C++, C# and it's really cool.
In the near future I want to learn Java, Python for AI.   

- I am currently learning C, C++ and sometimes spend a little time learning C#.

- I'm looking for someone who understands that he might get a good software engineer in the future.

- How to reach me:

**Way**   | **link**
---:      | :---
LinkedIn: | [go to LinkedIn](https://www.linkedin.com/in/сергей-селивончик-221105207)
email:    | yoricsv@yandex.ru
mobile:   | +375(29) 263-99-00


---
# MY TASKS LIST

- [ ] For compiling SFML on Linux I need to be install next packages:
   - [ ] FreeType Engine (*TrueType font rendering engine*) [- download package][1]
   - [ ] x11
      (*use following to install the package*) [- download package][2]
      ```bash
      sudo dnf install xorg-x11-apps      
      ```
      or 
      ```bash
      sudo rpm install @base-x      
      ```
      - [*System X Windows Manual*][3]
      - [*Configuring X Windows System*][4]
   - [ ] XRandR (*configuration utility X Window System*) [- download package][5]
   - [ ] Udev (*creates and removes device nodes*) [- download package][6]
   - [ ] OpenGL (*API for rendering 2D and 3D vector graphics*) [- download package][7]
   - [ ] OpenAL (*API for rendering of multichannel audio*) [- download package][8]
   - [ ] FLAC (*Free Lossless Audio Codec*) [- download package][9]
   - [ ] Ogg (*streaming and multimedia processing format*) [- download package][10]
   - [ ] Vorbis (*audio encoding format*) [- download package][11]
   - [ ] VorbisEnc (*encoder of raw float audio into a Vorbis stream*) [- download package][12]
   - [ ] VorbisFile (*API for decoding audio streams*) [- download package][13]
   - [ ] PThread (*POSIX Threads is a parallel execution model*) [- download package][14]

[1]: (https://rpmfind.net/linux/fedora/linux/releases/34/Everything/x86_64/os/Packages/f/freetype-2.10.4-3.fc34.i686.rpm)
[2]: (https://rpmfind.net/linux/fedora/linux/releases/34/Everything/x86_64/os/Packages/l/libX11-1.7.0-3.fc34.x86_64.rpm)
[3]: (https://docs.fedoraproject.org/ru-RU/Fedora_Core/5/html/Release_Notes/sn-Xorg.html)
[4]: (https://docs.fedoraproject.org/en-US/quick-docs/configuring-x-window-system-using-the-xorg-conf-file/)
[5]: (https://fedora.pkgs.org/34/fedora-x86_64/libXrandr-devel-1.5.2-6.fc34.x86_64.rpm.html)
[6]: (https://rpmfind.net/linux/fedora/linux/updates/34/Everything/x86_64/Packages/s/systemd-udev-248.3-1.fc34.x86_64.rpm)
[7]: (https://rpmfind.net/linux/fedora/linux/releases/33/Everything/x86_64/os/Packages/l/libglvnd-opengl-1.3.2-2.fc33.x86_64.rpm)
[8]: (https://rpmfind.net/linux/fedora/linux/releases/34/Everything/x86_64/os/Packages/o/openal-soft-1.19.1-12.fc34.x86_64.rpm)
[9]: (https://rpmfind.net/linux/fedora/linux/releases/34/Everything/x86_64/os/Packages/f/flac-1.3.3-7.fc34.x86_64.rpm)
[10]: (https://rpmfind.net/linux/fedora/linux/releases/34/Everything/x86_64/os/Packages/l/libogg-1.3.4-4.fc34.x86_64.rpm)
[11]: (https://rpmfind.net/linux/fedora/linux/releases/34/Everything/x86_64/os/Packages/v/vorbis-tools-1.4.2-2.fc34.x86_64.rpm)
[12]: (https://fedora.pkgs.org/34/fedora-x86_64/libvorbis-devel-1.3.7-3.fc34.x86_64.rpm.html)
[13]: (https://fedora.pkgs.org/34/fedora-x86_64/libvorbis-devel-1.3.7-3.fc34.x86_64.rpm.html)
[14]: (https://rpmfind.net/linux/fedora/linux/releases/34/Everything/x86_64/os/Packages/g/glibc-2.33-5.fc34.x86_64.rpm)

---
<br/>

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=yoricsv)](https://github.com/anuraghazra/github-readme-stats)

<!---
yoricsv/yoricsv is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->








<!--
  ******************************************************************************
  * @file           : README.md
  * @brief          : Short description of the project
  ******************************************************************************
  * @attention
  *
  * The PROJECT STRUCTURE part describes the common structure of the project
  * in order to understand where the code is and where the Cmake generator 
  * finds the source files.
  *
  ******************************************************************************
-->

<!-- *********************** PROJECT STRUCTURE (blank) ************************* //

[<Project_name>]
  |
  |->[.build]           // directory for building system
  |   |
  |   |->[CMakeFiles]   // all necessary directories and files for CMake build 
  |                     // generator
  |
  |->[.git]             // all necessary directories and files for Git
  |
  |
  |->[.settings]        // contains project file directories for different IDEs
  |
  |
  |->[debug]            // contains compiller, linker, object files
  |   |
  |   |->[logs]         // contains logs
  |
  |->[<Project_name Repository>]
  |   |
  |   |->[inc]          // contains public/private HEADERS (*.h) (might be split
  |   |                 // into two directories public and privat)
  |   |->[res]          // contains static/dynamic LIBRARIES     (might be split
  |   |                 // into two directories static and dynamic)
  |   |->[src]          // contains SOURCE files/code(s)   (.с; .cpp)
  |   |
  |   |->[ui]           // these directories for applications with USER INTERFACE
  |                     // (might contains QML)
  |
  |->[output]           // directory for executable applications
  |
  |->[tests]            // directory for unit tests
  |
  |
  |--- .gitignore
  |--- CMakeLists.txt
  |--- README.md

  -->
