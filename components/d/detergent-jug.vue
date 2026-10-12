<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oxwfoi55x"/><rect class="hifqwccwu"/><path class="hroqw1bmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:detergent-jug" /></template>
<style>
.hifqwccwu {
  width: 4.5px;
  height: 3px;
  x: 8.25px;
  y: 2.75px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hroqw1bmm {
  d: path("M13.75 9.25h2.5v4.5h-2.5Z");
}

.oxwfoi55x {
  d: path("M4.75 19.25v-8.5q0-2 1.41-3.41l.18-.18q1.41-1.41 3.41-1.41h7.5q2 0 2 2v11.5q0 2-2 2H6.75q-2 0-2-2");
}

</style>
