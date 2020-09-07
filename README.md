
# React Native Foundations
![React Native, Android, ios Logo](https://www.futuremind.com/m/cache/c8/15/c8150d863e584ed42ccfbdc3f3f1aa3a.jpg)
****
This lesson was created by Dominic Cobb, www.linkedin.com/in/dominiccobb
## Who this lesson is for?
* Recent Bootcamp Grads with no previous React-Native exposure
* Web developers interested in mobile dev
* Fellow Geeks like me
## Goals of this lesson
* Why use React Native?
* Limitations of React Native
* What is Expo?
* How to Getting started
* Basic Components Overview

## Course Structure

- What is React Native?
- React CLI vs Expo
- Development Setup
- Basic Components
- Styling
- Navigation
- Forms
- Networking
- Animations
- Permissons
- Conclusion

## Important Resources 
* Official React Native Docs [https://reactnative.dev/](https://reactnative.dev/)
* Expo Docs [https://docs.expo.io/guides/](https://docs.expo.io/guides/)
* React Navigation [https://reactnavigation.org/docs/getting-started](https://reactnavigation.org/docs/getting-started)
* Reanimated [https://docs.swmansion.com/react-native-reanimated/](https://docs.swmansion.com/react-native-reanimated/)

## Lesson 0 = What is React Native?
React Native is a mobile development framework used to make cross platform mobile (IOS/Android), web, and tv applications 

Direct from the React Native Documentation
> React Native combines the best parts of native development with React, a best-in-class JavaScript library for building user interfaces. 
> 
> Use a little—or a lot. You can use React Native today in your existing Android and iOS projects or you can create a whole new app from scratch.
> 
>React components wrap existing native code and interact with native APIs via React’s declarative UI paradigm and JavaScript. This enables native app development for whole new teams of developers, and can let existing native teams work much faster.

"Similar to React for the Web, React Native applications are written using a mixture of JavaScript and XML-esque markup, known as JSX.  Then, under the hood, the React Native “bridge” invokes  the native rendering APIs in Objective-C (for iOS) or Java (for Android). 

Thus, your application will render using real mobile UI components,  _not_  webviews, and will look and feel like any other mobile application. React Native also exposes JavaScript interfaces for platform APIs, so your React Native apps can access platform features like the phone camera, or the user’s location.

The fact that React Native actually renders using its host platform’s standard rendering APIs enables it to stand out from most existing methods of cross-platform application development, like Cordova or Ionic. Existing methods of writing mobile applications using combinations of JavaScript, HTML, and CSS typically render using webviews. While this approach can work, it also comes with drawbacks, especially around performance. Additionally, they do not usually have access to the host platform’s set of native UI elements. When these frameworks do try to mimic native UI elements, the results usually “feel” just a little off; reverse-engineering all the fine details of things like animations takes an enormous amount of effort, and they can quickly become out of date.

In contrast, React Native actually translates your markup to real, native UI elements, leveraging existing means of rendering views on whatever platform you are working with. Additionally, React works separately from the main UI thread, so your application can maintain high performance without sacrificing capability. The update cycle in React Native is the same as in React: when `props` or `state` change, React Native re-renders the views. The major difference between React Native and React in the browser is that React Native does this by leveraging the UI libraries of its host platform, rather than using HTML and CSS markup."

-Oreilly 

### A few companies using React Native
<img src="https://reactnative.dev/img/showcase/facebook.png" alt="drawing" width="100"/><img src="https://reactnative.dev/img/showcase/instagram.png" alt="drawing" width="100"/><img src="https://reactnative.dev/img/showcase/pinterest.png" alt="drawing" width="100"/><img src="https://reactnative.dev/img/showcase/ubereats.png" alt="drawing" width="100"/><img src="https://reactnative.dev/img/showcase/tesla.png" alt="drawing" width="100"/> <img src="https://reactnative.dev/img/showcase/salesforce.png" alt="drawing" width="100"/> <img src="https://reactnative.dev/img/showcase/wix.png" alt="drawing" width="100"/><img src="https://reactnative.dev/img/showcase/walmart.png" alt="drawing" width="100"/><img src="https://reactnative.dev/img/showcase/bloomberg.png" alt="drawing" width="100"/>

* Facebook
* Facebook Ads
* Facebook Analytics
* Instagram
* Oculus
* Skype
* Discord
* Bloomberg
* Pinterest
* Tesla
* Uber Eats
* Salesforce
* Wix
* Vogue
* and many more!

## Lesson 1 = React Cli vs. Expo Cli

### What is Expo anyway?
[Expo](http://expo.io/) is a framework and a platform for universal React applications. It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

**Expo SDK**  provides access to tons of native API's for which you would otherwise need to use a module or write your own. Expo is an exceptional tool for someone who is just getting started with  **React Native**  as it takes off all the complexity while builing a  **React Native**  app.

The only downside to using Expo is that you cannot extend the native functionality while writing your app. Which means, if you wish to integrate a third party native library or extend app functionality with native code, then you simply cannot do it. This is because Expo projects do not reveal the native  `iOS`  and  `Android`  projects that  `react-native`  cli does.

### Cons of React Native Cli
The major downside for the **React Native Cli** is that you need to setup build chains for both platforms on your system. For Android you will need Android Studio and for iOS you will need to setup Xcode so that you can build and test on your devices. That is specially cumbersome for someone who is not aware of these tools and build systems, specially when building for production.

### Comparison
|Features|React Native Cli|Expo Cli|
|--|--|--|
||  | |

## Lesson 2 = Development Setup

#### In this course we will be using the Expo SDK, I believe as do many that this is the best way to get familiar with **React Native** development

First we will install the Expo cli

```npm  install -g expo-cli```

Next we will initiate a new expo project

```expo init foundations --npm```  

We will select managed workflow   

--------SHOW SCREENSHOT--------

```cd foundations``` 

Then finally we will run the app

```expo start```


## Lesson 3 = Basic Components
## Lesson 4 = Styling
## Lesson 5 = Navigation
## Lesson 6 = Forms
## Lesson 7 = Networking
## Lesson 8 = Animations
## Lesson 9 = Permissions
## Wrap up & further steps
## Amazing Packages for React Native

##  Credits

This lesson was created by [Dominic Cobb](https://www.linkedin.com/in/dominiccobb)

Dominic Cobb is a Software Engineer Based in southern California. 

<img src="https://i.ibb.co/16pT7qD/C91-F83-B7-F11-B-42-C8-8-C4-F-A45-B1559935-E-1-201-a.jpg" alt="drawing" width="450"/>


#### Special thanks to 
- [Arthur Bernier Jr.](https://www.linkedin.com/in/developmentandmanagement/)
- [Alex Merced](https://www.linkedin.com/in/alexmerced/)
- [Arman Sadri](https://www.linkedin.com/in/arman-sadri-3b328a30/)
- [William Candillon](https://www.linkedin.com/in/wcandillon/)
- [Kadi Kraman](https://www.linkedin.com/in/kadi-kraman-922a7277/?originalSubdomain=uk)
- [Pradip Debnath](https://www.linkedin.com/in/itzpradip/)

#### Sources

* Official React Native Docs [https://reactnative.dev/](https://reactnative.dev/)
* Expo Docs [https://docs.expo.io/guides/](https://docs.expo.io/guides/)
* React Navigation [https://reactnavigation.org/docs/getting-started](https://reactnavigation.org/docs/getting-started)
* Reanimated [https://docs.swmansion.com/react-native-reanimated/](https://docs.swmansion.com/react-native-reanimated/)
* https://xencov.com/blog/react-native-expo-vs-react-native-cli#:~:text=Expo%20SDK%20and%20CLI&text=The%20major%20plus%20which%20falls,both%20iOS%20and%20Android%20devices.
* Oreilly [https://www.oreilly.com/library/view/learning-react-native/9781491929049/ch01.html](https://www.oreilly.com/library/view/learning-react-native/9781491929049/ch01.html)
