#!groovy

dockerNode("maven:3.3.3-jdk-8") {
  git "https://github.com/wakaleo/game-of-life"
  sh 'mvn clean package'
}
