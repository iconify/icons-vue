<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zfy8wlbwe"/><path class="hoxzee01i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aloe" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hoxzee01i {
  d: path("M12 15.5V3.75M9.5 15.5C9 11.75 7.25 9 4.25 7.5m10.25 8c.5-3.75 2.25-6.5 5.25-8M7 15.5c-.75-1.25-2-2-4.25-2.25M17 15.5c.75-1.25 2-2 4.25-2.25");
}

.zfy8wlbwe {
  d: path("M7.75 15.5h8.5q1.25 0 .98 1.22l-.71 3.31q-.27 1.22-1.52 1.22H9q-1.25 0-1.52-1.22l-.71-3.31q-.27-1.22.98-1.22");
}

</style>
