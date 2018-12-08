# Connect CGOS bot for Linux

## Edit config.txt

Replace ${username} to your user name
Replace ${password} to your pass word
Replace ${command} to your bot start script

## Connect CGOS

```bash
$ ./cgos.sh
```

## Stop
```bash
cp sentinel/abort.txt ./
```
Engine will quit after next game.

## View games

```bash
./cgosview yss-aya.com 6819
```
Wait for a while, you will see a game list.
