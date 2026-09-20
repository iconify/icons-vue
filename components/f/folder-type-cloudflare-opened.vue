<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="t__v0db3i"><path class="qxoxqxb3q"/><path class="dvkqa0e4s"/></g><path class="a s7yy120yv"/><path class="b eyz4xmbvt"/><path class="c jgx8cixis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cloudflare-opened" /></template>
<style>
.dvkqa0e4s {
  d: path("M4.3 26.5h25.2l-3.8-12.8H.5z");
}

.eyz4xmbvt {
  fill: var(--svg-color--f48120, #f48120);
  d: path("M23.68 26.208a1.5 1.5 0 0 0-.158-1.371a1.63 1.63 0 0 0-1.109-.58l-9.181-.106c-.053 0-.106-.053-.158-.053a.1.1 0 0 1 0-.159c.052-.105.105-.158.21-.158l9.235-.105a3.32 3.32 0 0 0 2.691-2.005l.528-1.372c0-.053.052-.106 0-.159a6.013 6.013 0 0 0-11.556-.633a2.88 2.88 0 0 0-1.9-.528a2.75 2.75 0 0 0-2.427 2.428a2.9 2.9 0 0 0 .053.95a3.853 3.853 0 0 0-3.747 3.851a2.2 2.2 0 0 0 .053.58a.17.17 0 0 0 .158.16H23.31c.106 0 .212-.054.212-.16z");
}

.jgx8cixis {
  fill: var(--svg-color--faad3f, #faad3f);
  d: path("M26.582 20.299h-.264c-.053 0-.105.052-.158.105l-.37 1.267a1.5 1.5 0 0 0 .159 1.371a1.63 1.63 0 0 0 1.108.58l1.952.106c.053 0 .106.053.159.053a.1.1 0 0 1 0 .158c-.053.106-.106.159-.211.159l-2.006.105a3.32 3.32 0 0 0-2.69 2.005l-.106.475c-.053.053 0 .159.105.159h6.965a.14.14 0 0 0 .159-.159a5.7 5.7 0 0 0 .21-1.372a5.045 5.045 0 0 0-5.012-5.012");
}

.qxoxqxb3q {
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21zm0 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1v2.1z");
}

.s7yy120yv {
  fill: var(--svg-color--fff, #fff);
  d: path("m29.22 21.037l-2.955-.686l-.527-.21l-13.561.105v6.543l17.043.053z");
}

.t__v0db3i {
  fill: var(--svg-color--cd7b05, #cd7b05);
}

</style>
