
<div align="center">

  <h1><b>Enumerable</b></h1>

</div>


<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  <!-- - [🚀 Live Demo](#live-demo) -->
- [💻 Getting Started](#getting-started)
- [👥 Author](#author)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

**Enumerable** is a Ruby project that demonstrates a custom implementation of certain methods from the Enumerable module.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

- Ruby

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.ruby-lang.org/en/">Ruby</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- Custom implementation of the each method for the MyList class.<br>
- Custom implementations for all?, any?, and filter methods in the MyEnumerable module.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->

<!-- ## 🚀 Live Demo <a name="live-demo"></a>

> Add a link to your deployed project.

- [Live Demo Link](<replace-with-your-deployment-URL>)

 -->

<!-- GETTING STARTED -->

## Getting Started

- Create an instance of the MyList class.
- Utilize the custom methods from the MyEnumerable module to work with the list.
- Test your code using the provided examples.

```ruby
require_relative 'my_list'

# Create our list
list = MyList.new(1, 2, 3, 4)

# Test #all?
puts list.all? { |e| e < 5 }  # Should output: true
puts list.all? { |e| e > 5 }  # Should output: false

# Test #any?
puts list.any? { |e| e == 2 }  # Should output: true
puts list.any? { |e| e == 5 }  # Should output: false

# Test #filter
puts list.filter(&:even?).inspect  # Should output: [2, 4]
```
### Prerequisites

In order to run this project you need:

```
    postgres
```

### Setup

Clone this repository to your desired folder:

```sh
  git clone https://github.com/yaredtekle022/ruby-enumerable
```
go inside this project with:

```sh
  cd ruby-enumerable
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Author <a name="author"></a>

👤 Djibril Mugisho

- GitHub: [@DjibrilM](https://github.com/DjibrilM)
- Twitter: [@DjibrilM](https://twitter.com/DjibrilMugisho/)
- LinkedIn: [Djibril](https://www.linkedin.com/in/djibril-mugisho/)

👤 **Yared Tekle**

- GitHub: [@yaredtekle](https://github.com/yaredtekle022/)
- Twitter: [@yaredtekle](https://twitter.com/YaredTekle22/)
- LinkedIn: [yaredtekle](https://www.linkedin.com/in/yared-tekle-5708ba22b/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- **Add additional custom methods for MyEnumerable**
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING --> 

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

Thank you for taking the time to explore this project! Your support means a lot to me. If you find my project valuable and would like to contribute, here is one way you can support me:

 - <b>Star the project ⭐️</b>: Show your appreciation by starring this GitHub repository. It helps increase visibility and lets others know that the project is well-received.

 - <b>Fork the project 🍴 🎣</b>: If you're interested in making improvements or adding new features, feel free to fork the project. You can work on your own version and even submit pull requests to suggest changes.

 - <b>Share with others 🗺️</b>: Spread the word about this project. Share it on social media, mention it in relevant forums or communities, or recommend it to colleagues and friends who might find it useful.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to express my sincere gratitude to <br><br>
1, [Microverse](https://github.com/microverseinc), the dedicated reviewers, and collaborators. Your unwavering support, feedback, and collaborative efforts have played an immense role in making this journey a resounding success. I am truly grateful for your contributions and for being an integral part of my achievements. Thank you for your continued support.
<br><br>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>