<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lz9ycyb6v"/><path class="y6voxlbco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cycle-highway" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lz9ycyb6v {
  d: path("m2 21.5l5-19m15 19l-5-19M6 17.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m6.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.y6voxlbco {
  d: path("M8.75 17.25h3.5l2.5-5m.5 5l-1.5-6.75h2m-5.25 2.25l1.75 4.5m-2.75-4.5h2.25");
}

</style>
