---
layout: home

hero:
  name: "Image Processing"
  text: "一個C++影像處理庫"
  tagline: 輕量化、高移植性
  actions:
    - theme: brand
      text: Read Docs
      link: /pages/setup
    - theme: alt
      text: View Source
      link: https://github.com/yappy2000d/Image-Processsing

features:
  - icon: <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="100" height="100" viewBox="0 0 48 48"><path fill="#00549d" fill-rule="evenodd" d="M22.903,3.286c0.679-0.381,1.515-0.381,2.193,0 3.355,1.883,13.451,7.551,16.807,9.434C42.582,13.1,43,13.804,43,14.566c0,3.766,0,15.101,0,18.867 c0,0.762-0.418,1.466-1.097,1.847c-3.355,1.883-13.451,7.551-16.807,9.434c-0.679,0.381-1.515,0.381-2.193,0 -3.355-1.883-13.451-7.551-16.807-9.434C5.418,34.899,5,34.196,5,33.434c0-3.766,0-15.101,0-18.867 c0-0.762,0.418-1.466,1.097-1.847C9.451,10.837,19.549,5.169,22.903,3.286z" clip-rule="evenodd"></path><path fill="#0086d4" fill-rule="evenodd" d="M5.304,34.404C5.038,34.048,5,33.71,5,33.255 c0-3.744,0-15.014,0-18.759c0-0.758,0.417-1.458,1.094-1.836c3.343-1.872,13.405-7.507,16.748-9.38 c0.677-0.379,1.594-0.371,2.271,0.008c3.343,1.872,13.371,7.459,16.714,9.331c0.27,0.152,0.476,0.335,0.66,0.576L5.304,34.404z" clip-rule="evenodd"></path><path fill="#fff" fill-rule="evenodd" d="M24,10c7.727,0,14,6.273,14,14s-6.23,14-14,14 s-14-6.273-14-14S16.273,10,24,10z M24,17c3.863,0,7,3.136,7,7c0,3.863-3.137,7-7,7s-7-3.137-7-7C17,20.136,20.136,17,24,17z" clip-rule="evenodd"></path><path fill="#0075c0" fill-rule="evenodd" d="M42.485,13.205c0.516,0.483,0.506,1.211,0.506,1.784 c0,3.795-0.032,14.589,0.009,18.384c0.004,0.396-0.127,0.813-0.323,1.127L23.593,24L42.485,13.205z" clip-rule="evenodd"></path><path fill="#fff" fill-rule="evenodd" d="M31 21H33V27H31zM38 21H40V27H38z" clip-rule="evenodd"></path><path fill="#fff" fill-rule="evenodd" d="M29 23H35V25H29zM36 23H42V25H36z" clip-rule="evenodd"></path></svg>
    title: 純 C++
    details: 使用純C++11實現，無需任何第三方庫。
  - icon: ⚙️
    title: 功能導向
    details: 無GUI介面。將精力放在影像處理算法上。
  - icon: 🚀
    title: 高效
    details: 使用SIMD指令集來提高運行速度。
  - icon: 📦
    title: 開源
    details: 遵循MIT許可協議。
---

## 與Windows C++/CLI的比較

| 特性 | Windows C++/CLI | Image Processing |
| --- | --- | --- |
|  語言  | C++/CLI | 純C++11 |
|  GUI   | :white_check_mark: | :x: |
| 移植性 | :x: | :white_check_mark: |
|  開源  | :x: | :white_check_mark: |

與其使用Windows C++/CLI讓C++能夠調用.NET Framework，不如直接去使用C#。如果想製作一個GUI應用程式，那麼Qt或Tk會是移植性更好的選擇。Image Processing專注於影像處理算法，不提供GUI介面。