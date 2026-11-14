<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wquh2jb1d"/><path class="tba-6ialp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aquarium-plant" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tba-6ialp {
  d: path("M3 6.5q4.5-1.5 9 0t9 0M9.5 21c-2.5-2.5 2.5-5.5 0-8c-2-2 .5-3 0-3.5m5 11.5c2.5-3-2.5-5.5 0-8.5");
}

.wquh2jb1d {
  d: path("M3 4v15a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V4");
}

</style>
