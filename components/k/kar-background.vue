<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGAGAgMz7E)" class="r4i437pya"/><path class="e0-c10b5c"/></g><defs><linearGradient id="SVGAGAgMz7E" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="wlpjn2qoa"/><stop offset="1" class="i8uan0fox"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kar-background" /></template>
<style>
.e0-c10b5c {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.2 9.333h1.893c.246 0 .966-.25 1.888-1.125A479 479 0 0 1 15.467 4h4l-6.4 6.133l6.346 8.8h-3.146L13.6 15.2c.341.816.544 2.89-.101 4.8c.16-1.845-.86-3.872-1.056-4.133c-.176-.235-1.11-2.102-1.558-3.003c-.405-1.75 1.419-3.504 2.384-4.16c-1.27-.81-2.4.128-2.805.693c-.725-.096-1.35.406-1.573.667l-2.102 2.97c-.48.694-.981.742-1.173.678c.395.933 1.35.453 1.776.101c.107.704-.197 1.12-.363 1.238a1.32 1.32 0 0 0 1.136-1.03c.16.235.427 1.163.208 2.96a2.4 2.4 0 0 1-1.386 1.952l-.032-.005H4.533V4H7.2zm2.117 1.627c0-.31.17-.933.87-.944c-.06.715-.608.928-.87.944");
}

.ft5dv1b6b {
  fill: none;
}

.i8uan0fox {
  stop-color: var(--svg-color--f01e52, #f01e52);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wlpjn2qoa {
  stop-color: var(--svg-color--fb3d42, #fb3d42);
}

</style>
