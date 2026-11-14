<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pbdxvfmoc"/><path class="t2wrq_y2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cute-cow" /></template>
<style>
.pbdxvfmoc {
  d: path("M9.75 3h4.5a3.5 3.5 0 0 1 3.5 3.5v11a3.5 3.5 0 0 1-3.5 3.5h-4.5a3.5 3.5 0 0 1-3.5-3.5v-11A3.5 3.5 0 0 1 9.75 3Zm-3.5 5C4.5 6.75 2.5 7 2.5 8.25c0 1.5 2 2.25 3.75 1.75m11.5-2c1.75-1.25 3.75-1 3.75.25c0 1.5-2 2.25-3.75 1.75");
}

.t2wrq_y2f {
  d: path("M10.5 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1.25 3.75h.01m5.49 0h.01M6.25 15.5c3.25-1.5 8.25-1.5 11.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
