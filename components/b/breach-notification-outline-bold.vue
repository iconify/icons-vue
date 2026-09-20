<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k70w93buq"/><path class="f4yp5uw0u"/><path class="bz9ijib4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:breach-notification-outline-bold" /></template>
<style>
.bz9ijib4d {
  d: path("M13.5 8.5 11 11h2.5L11 13.5");
}

.f4yp5uw0u {
  d: path("M14 18.5a2 2 0 0 1 -4 0");
}

.k70w93buq {
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
