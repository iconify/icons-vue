<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r30-akbyd"/><path class="jy8fribza"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:autumn-leaves-falling" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jy8fribza {
  d: path("M15 20q-.5-5.5 5-5q.5 5.5-5 5m-1.25 1.25l4.75-4.75M12 6h6a2 2 0 1 0-2-2");
}

.r30-akbyd {
  d: path("M3.5 8.5q-.5-5.5 5-5q.5 5.5-5 5M2.25 9.75L7 5m2.5 9.5q-.5-5.5 5-5q.5 5.5-5 5m-1.25 1.25L13 11");
}

</style>
