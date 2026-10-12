<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uzp2y2seh"/><path class="w99emkb_d"/><circle class="z2s2z540y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:branch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzp2y2seh {
  d: path("M2.75 18.75C9 17.5 14.5 13.5 19.5 5.75");
}

.w99emkb_d {
  d: path("M8.5 17.75c.5 2 2 3.25 4 3.5c-.25-2-1.75-3.25-4-3.5m3.25-3c-1.75-1.25-2.5-3-2-5.25c1.75 1.25 2.5 3 2 5.25m4.7-4.8c-1.73-.86-2.65-2.31-2.52-4.38c1.73.86 2.65 2.31 2.52 4.38m-3.2 3.35q2.25.75 4.5 0");
}

.z2s2z540y {
  cx: 19px;
  cy: 13.3px;
  r: 1.25px;
}

</style>
