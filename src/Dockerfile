FROM python:3.12.0a3-buster
COPY ./src/requirements.txt /app/requirements.txt
COPY ./src/app /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python3"]
CMD ["main.py"]