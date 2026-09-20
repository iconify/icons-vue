<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ypjl1rb6b"/><path class="d38l4c_id"/><path class="mg0m-7bua"/><path class="mgo0l9ojs"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atpay-background" /></template>
<style>
.d38l4c_id {
  fill: var(--svg-color--fff, #fff);
  d: path("m16.782 16.47l1.05 1.03c.09.08.085.215 0 .3a8.24 8.24 0 0 1-5.57 2.2c-4.525.035-8.235-3.56-8.245-7.985S7.672 4 12.197 4c2.95 0 5.54 1.535 6.98 3.83l-1.405 1.375C16.732 7.225 14.622 6 12.197 6c-3.45 0-6.16 2.65-6.18 6.015c-.02 3.375 2.55 5.935 6 5.985c1.7.025 3.33-.485 4.47-1.535a.215.215 0 0 1 .3.005z");
}

.ft5dv1b6b {
  fill: none;
}

.mg0m-7bua {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.018 8.07v.6a4 4 0 0 0-1.99-.67a4.095 4.095 0 0 0-4.01 4c0 1.065.55 2.025 1.26 2.72l1.35-1.32a1.87 1.87 0 0 1-.61-1.4a2.085 2.085 0 0 1 2.01-2a1.97 1.97 0 0 1 1.99 2v1l2.004-2.05V8.1c0-.05-.085-.1-.144-.1h-1.7c-.06 0-.16.015-.16.07");
}

.mgo0l9ojs {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.972 9.52a.21.21 0 0 1-.05.215l-4.95 4.84l-.285.28l-.835.814a2.595 2.595 0 0 1-3.61 0l-.965-.95l1.35-1.32l.975.955c.25.25.65.25.9 0l6.675-6.524c.33.525.6 1.095.8 1.69z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ypjl1rb6b {
  fill: var(--svg-color--61d5c7, #61d5c7);
  d: path("M24 0H0v24h24z");
}

</style>
