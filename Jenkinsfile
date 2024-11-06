node {
   stage('clone') {
        git branch: 'main', url: 'https://github.com/yanikdiallo/jenkinsdepot.git'
    }
    
    stage('build') {
        sh 'javac Main.java'
    }
    
    stage('Run') {
        sh 'java Main'
    }


}
