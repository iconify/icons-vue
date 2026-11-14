<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="de0p5lk2v"/><path class="z7xm80c7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bolt-and-nut" /></template>
<style>
.de0p5lk2v {
  d: path("M4.75 2.5h4.5A1.75 1.75 0 0 1 11 4.25v.5A1.75 1.75 0 0 1 9.25 6.5h-4.5A1.75 1.75 0 0 1 3 4.75v-.5A1.75 1.75 0 0 1 4.75 2.5m.25 4v13a2 2 0 0 0 4 0v-13m8.75 3.433l2.397 1.384a1.5 1.5 0 0 1 .75 1.299v2.768a1.5 1.5 0 0 1-.75 1.299l-2.397 1.384a1.5 1.5 0 0 1-1.5 0l-2.397-1.384a1.5 1.5 0 0 1-.75-1.299v-2.768a1.5 1.5 0 0 1 .75-1.299l2.397-1.384a1.5 1.5 0 0 1 1.5 0M5 10.5l4-1m-4 4l4-1m-4 4l4-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7xm80c7o {
  d: path("M15.25 14a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
