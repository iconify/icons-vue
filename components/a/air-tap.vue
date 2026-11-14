<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="guyplobse"/><path class="omqe-motk"/><path class="zdli8kbcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:air-tap" /></template>
<style>
.guyplobse {
  d: path("M10 21.5v-11a2 2 0 0 1 4 0v4h3a2 2 0 0 1 2 2v5");
}

.omqe-motk {
  d: path("M7 11.5a5 5 0 1 1 10 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdli8kbcg {
  d: path("M4.25 12a8 8 0 1 1 15.5 0");
}

</style>
