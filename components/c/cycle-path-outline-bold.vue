<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kum2ffbcf"/><path class="ok8xuubvg"/><path class="i--1v6y7j"/><path class="yyr7ulb8d"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cycle-path-outline-bold" /></template>
<style>
.i--1v6y7j {
  d: path("m6 12 3 -3h6l3 3");
}

.kum2ffbcf {
  d: path("M2.5 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.ok8xuubvg {
  d: path("M14.5 12a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yyr7ulb8d {
  d: path("M9 5v4");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
