FROM frolvlad/alpine-oraclejdk8:slim
MAINTAINER erdaoya

ADD @project.build.finalName@.jar @project.build.finalName@.jar
RUN sh -c 'touch /@project.build.finalName@.jar'

CMD ["sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /@project.build.finalName@.jar" ]
