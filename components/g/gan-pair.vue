<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p-0j4sb-j"/><path class="j0kb8topb"/><circle class="d4da7x21x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gan-pair" /></template>
<style>
.d4da7x21x {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0kb8topb {
  d: path("M7 4.5Q7.3 6.7 9.5 7Q7.3 7.3 7 9.5Q6.7 7.3 4.5 7Q6.7 6.7 7 4.5m7 .25h2.25a2.5 2.5 0 0 1 2.5 2.5v2M17 7.5l1.75 1.75L20.5 7.5M10 19.25H7.75a2.5 2.5 0 0 1-2.5-2.5v-2M3.5 16.5l1.75-1.75L7 16.5");
}

.p-0j4sb-j {
  width: 8.5px;
  height: 8.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
