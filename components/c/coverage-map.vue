<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lu3wubcot"/><path class="xihuptbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coverage-map" /></template>
<style>
.lu3wubcot {
  d: path("M2 5.5L8.5 3l7 2.5L22 3v15.5L15.5 21l-7-2.5L2 21ZM12 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xihuptbzt {
  d: path("M9.5 9.5a3.5 3.5 0 0 0 0 5m5-5a3.5 3.5 0 0 1 0 5M7.75 7.75a6 6 0 0 0 0 8.5m8.5-8.5a6 6 0 0 1 0 8.5");
}

</style>
