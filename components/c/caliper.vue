<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vx557u7jh"/><path class="bu_9etb6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caliper" /></template>
<style>
.bu_9etb6p {
  d: path("M12 4.5v1.75m3-1.75v1.75m3-1.75v1.75M3.5 8.5h1.75q.75 0 .75.75v8.5q0 .75-.23.04L2.98 9.21q-.23-.71.52-.71m6.25 0h1.75q.75 0 .52.71l-2.79 8.58Q9 18.5 9 17.75v-8.5q0-.75.75-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vx557u7jh {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 4.5px;
  rx: 1.25px;
}

</style>
