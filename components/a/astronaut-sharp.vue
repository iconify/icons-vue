<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="q71tojf4b"/><path class="rnbhx_1yy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:astronaut-sharp" /></template>
<style>
.q71tojf4b {
  cx: 12px;
  cy: 8.25px;
  r: 5.5px;
}

.rnbhx_1yy {
  d: path("M8.75 6h6.5v4.5h-6.5zM5 21.25h15v-1c0-2.6-3.6-4-8-4s-8 1.4-8 4v1zm5.5-2.5h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
