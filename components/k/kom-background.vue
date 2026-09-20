<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hd6uai29u"/><path class="bokbp7dca"/><path class="dekppwbkw"/><path class="b-2ilcv0m"/><path class="og6tabe0b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kom-background" /></template>
<style>
.b-2ilcv0m {
  fill: var(--svg-color--fff, #fff);
  d: path("m7 17.5l-2 1.25L6.995 20L9 18.75zM17 9l-2 1.25l2 1.25l2-1.25zM7 9.73L17 4v2.465L7 12z");
}

.bokbp7dca {
  fill: var(--svg-color--fff, #fff);
  d: path("M15 14.68V13l2-1l.05 3.72zm-4.145-2.66L15.53 9.3l.275-2.775l-7.34 3.25v2.245zm6.16 7.98L19 18.75L8.98 12.97l-2.225 1.15z");
}

.dekppwbkw {
  fill: var(--svg-color--fff, #fff);
  d: path("M5 4.935L7 4v13.82l-2 .935zm10 .29L17 4v5.285l-2 .965zm4-.05L17 4v5.25l2 1zm-10-.24L7 4v13.82l2 .935z");
}

.ft5dv1b6b {
  fill: none;
}

.hd6uai29u {
  fill: var(--svg-color--2b6def, #2b6def);
  d: path("M24 0H0v24h24z");
}

.og6tabe0b {
  fill: var(--svg-color--fff, #fff);
  d: path("m7 12l12 6.75V13l-2-1v3.5l-8.015-4.616z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
