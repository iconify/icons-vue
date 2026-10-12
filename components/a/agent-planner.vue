<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i48_wjb1d"/><path class="uv536fzze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:agent-planner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i48_wjb1d {
  width: 15.5px;
  height: 16px;
  x: 4.25px;
  y: 5.25px;
  rx: 2.5px;
}

.uv536fzze {
  d: path("M8.5 5.25v-1.5a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v1.5Zm-.75 5.25h5m-5 4h3m4.5-1.5q.39 2.86 3.25 3.25q-2.86.39-3.25 3.25q-.39-2.86-3.25-3.25q2.86-.39 3.25-3.25");
}

</style>
