<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oek034kyj"/><path class="pzyfl9k4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-wifi" /></template>
<style>
.oek034kyj {
  d: path("M11 16h.01M8.5 13.5q.182-.186.391-.343q.208-.158.437-.282q.229-.125.474-.214t.5-.141q.256-.052.516-.066q.26-.013.52.012q.259.025.512.088q.253.064.494.164M6 11a7 7 0 0 1 10 0");
}

.pzyfl9k4x {
  d: path("M3.5 8.5a10.5 10.5 0 0 1 15 0m0 5l3.5 1.25v2.75c0 2.5-1.75 4-3.5 4.5c-1.75-.5-3.5-2-3.5-4.5v-2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
