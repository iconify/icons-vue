<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yr23anbvh"/><rect class="g5p9dlbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desk-calendar" /></template>
<style>
.g5p9dlbck {
  width: 6.5px;
  height: 4.5px;
  x: 8.75px;
  y: 13.5px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yr23anbvh {
  d: path("M8 4.25v2.5m4-2.5v2.5m4-2.5v2.5m-9.5 0h11q1.5 0 1.68 1.49l1.39 11.52q.18 1.49-1.32 1.49H4.75q-1.5 0-1.32-1.49L4.82 8.24Q5 6.75 6.5 6.75m-2 3.75h15");
}

</style>
