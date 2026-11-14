<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="dzo-7_b_w"/><path class="p99bc7b8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:all-time-low" /></template>
<style>
.dzo-7_b_w {
  d: path("M7.5 6.5L11 12l3-2.5l3.5 7");
}

.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.p99bc7b8t {
  fill: currentColor;
  d: path("M16 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
