<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="odpv07k4y"/><path class="yxo_02wca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:competitor-analysis" /></template>
<style>
.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.odpv07k4y {
  d: path("m7 17l5-5l3 1.5L19.5 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yxo_02wca {
  d: path("m7 10.5l4 4.5l4.5-5.5l4 1");
}

</style>
