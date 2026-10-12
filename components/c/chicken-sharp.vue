<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wz-5p63qo"/><path class="yd5z59u0d"/><path class="ww59_qbwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chicken-sharp" /></template>
<style>
.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ww59_qbwz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 19v2.25M14.5 19v2.25");
}

.wz-5p63qo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.45 11.86L3 10.75l2.45-1.11a3.25 3.25 0 0 1 6.25.55c1.8 1.06 5.3 1.31 9.05-.19c.25 5.5-3.25 9-8 9c-4.25 0-7-2.5-7-5.5ZM5.5 4.5a1 1 0 0 1 2 0a1 1 0 0 1 2 0a1 1 0 0 1 2 0");
}

.yd5z59u0d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 10.5h.01");
}

</style>
