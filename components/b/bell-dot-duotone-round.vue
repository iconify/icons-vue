<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nas9t29dg"/><path class="m8wm8-4uy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-dot-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m8wm8-4uy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 13zc0 1 1 1 1 2a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2c0-1 1-1 1-2V9a6 6 0 0 1 6-6M9 17v1a3 3 0 0 0 6 0v-1m0-11a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.nas9t29dg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 18h-2a4 4 0 0 1-8 0H6a3 3 0 0 1-3-3c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C4 13.057 4 13.026 4 13V9c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 11 2a1 1 0 0 1 .919 1.394a6.62 6.62 0 0 0 .576 6.276c1.439 2.156 3.928 2.688 6.364 2.34a1 1 0 0 1 1.131.849c.007.052 0 .181.024.22c.048.081.128.148.193.214c.182.182.361.377.494.599c.201.335.299.718.299 1.108a3 3 0 0 1-3 3");
}

</style>
