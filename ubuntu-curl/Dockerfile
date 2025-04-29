FROM ubuntu

RUN apt-get update && apt-get install -y curl wget
RUN sh -c "$(wget -O- https://github.com/deluan/zsh-in-docker/releases/download/v1.2.1/zsh-in-docker.sh)" -- \
    -p https://github.com/zsh-users/zsh-syntax-highlighting
ENTRYPOINT [ "/bin/zsh" ]
CMD ["-l"]