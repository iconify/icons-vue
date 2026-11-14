<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="hnj4j1kyq"/><path class="nsty-m1wk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-line-multi" /></template>
<style>
.hnj4j1kyq {
  d: path("m7 15.5l4-5l3.5 2.5l5-6.5");
}

.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.nsty-m1wk {
  d: path("m7 8.5l4 4.5l4 2.5l4.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
