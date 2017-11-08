FROM nginx
RUN apt-get update && apt-get install -y --force-yes stress
EXPOSE 80
COPY ./stress.sh .
RUN chmod +x ./stress.sh
ENTRYPOINT ["./start.sh"]