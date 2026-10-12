<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cynvbx6lo"/><rect class="tug3cfpbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:karate-belt" /></template>
<style>
.cynvbx6lo {
  d: path("m9.43 3.36l2.14 3.03q.43.61.86 0l2.14-3.03Q15 2.75 15.71 3l3.58 1.25q.71.25.85.99l.97 5.02q.14.74-.61.74H19q-.75 0-.75.75v8.75q0 .75-.75.75h-11q-.75 0-.75-.75v-8.75Q5.75 11 5 11H3.5q-.75 0-.61-.74l.97-5.02q.14-.74.85-.99L8.29 3q.71-.25 1.14.36M12 7l2.25 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tug3cfpbi {
  width: 12.5px;
  height: 3px;
  x: 5.75px;
  y: 13.5px;
  rx: 0.5px;
}

</style>
