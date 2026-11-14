<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rd2ldhnkl"/><path class="w1qvdacdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bodysuit" /></template>
<style>
.rd2ldhnkl {
  d: path("M9 3L5.5 4.5C4.5 5 4 5.75 4 7v10.5h2.75L8 10v5c0 2.5 1.5 4 2.5 5v1.5h3V20c1-1 2.5-2.5 2.5-5v-5l1.25 7.5H20V7c0-1.25-.5-2-1.5-2.5L15 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1qvdacdk {
  d: path("M9 3q3 3 6 0m-3 16h.01");
}

</style>
