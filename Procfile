# create db
web: bin/rails db:migrate

# launch server
web: bin/rails server -p $PORT -e $RAILS_ENV

# web: bundle exec puma -C config/puma.rb
release: rake db:migrate