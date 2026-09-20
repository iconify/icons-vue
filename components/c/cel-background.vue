<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="jkunk4nfh"/><path class="nv5xanjkc"/><path class="fgyl-cb5x"/><path class="tkr7g8bil"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cel-background" /></template>
<style>
.fgyl-cb5x {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.588 11.06a1.412 1.412 0 1 0 0-2.823a1.412 1.412 0 0 0 0 2.823");
}

.ft5dv1b6b {
  fill: none;
}

.jkunk4nfh {
  fill: var(--svg-color--4055a6, #4055a6);
  d: path("M24 0H0v24h24z");
}

.nv5xanjkc {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.007 6.588c.136.207.146.622-.066.927c-.216.306-.8.504-1.27.047c-1.229-1.185-3.111-1.416-3.99-1.416A5.877 5.877 0 0 0 5.632 12c.047 2.428 1.69 5.854 6.047 5.854c1.223 0 3.275-.527 4.31-1.61c.18-.187.82-.07 1.045.212c.23.283.165.942-.094 1.163a8.28 8.28 0 0 1-5.266 1.91C7.44 19.53 4 16.16 4 12s3.435-7.53 7.68-7.53c3.53 0 5.238 1.982 5.327 2.118");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tkr7g8bil {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.588 10.118a.47.47 0 1 0 0-.941a.47.47 0 0 0 0 .94");
}

</style>
