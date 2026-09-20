<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a kjszasrxx"/><path class="b fs4burb6l"/><path class="c ykpnvbbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-cloudflare" /></template>
<style>
.fs4burb6l {
  fill: var(--svg-color--f48120, #f48120);
  d: path("M21.287 21.518a1.66 1.66 0 0 0-.174-1.51a1.8 1.8 0 0 0-1.22-.639l-10.108-.116c-.058 0-.116-.058-.174-.058a.11.11 0 0 1 0-.175c.058-.116.116-.174.232-.174l10.166-.116a3.66 3.66 0 0 0 2.962-2.207l.581-1.51c0-.059.058-.117 0-.175a6.62 6.62 0 0 0-12.721-.697a3.17 3.17 0 0 0-2.092-.581a3.026 3.026 0 0 0-2.672 2.672a3.2 3.2 0 0 0 .058 1.046a4.24 4.24 0 0 0-4.124 4.24a2.4 2.4 0 0 0 .058.64a.185.185 0 0 0 .174.174H20.88c.116 0 .233-.058.233-.175z");
}

.kjszasrxx {
  fill: var(--svg-color--fff, #fff);
  d: path("m27.386 15.826l-3.253-.756l-.58-.232l-14.93.116v7.203l18.763.058z");
}

.ykpnvbbxk {
  fill: var(--svg-color--faad3f, #faad3f);
  d: path("M24.482 15.012h-.29c-.059 0-.117.058-.175.116l-.407 1.395a1.66 1.66 0 0 0 .175 1.51a1.8 1.8 0 0 0 1.22.639l2.149.116c.058 0 .116.058.174.058a.11.11 0 0 1 0 .174c-.058.117-.116.175-.232.175l-2.208.116a3.66 3.66 0 0 0-2.962 2.207l-.116.523c-.058.058 0 .174.116.174h7.668a.154.154 0 0 0 .174-.174a6.3 6.3 0 0 0 .232-1.51a5.554 5.554 0 0 0-5.518-5.519");
}

</style>
