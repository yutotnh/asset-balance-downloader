FROM mcr.microsoft.com/devcontainers/python:3.11

USER 1000
ENV PATH $PATH:/home/vscode/.local/bin
RUN pip install playwright \
    && playwright install \
    && playwright install-deps
