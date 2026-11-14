<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-eja73-n"/><path class="f817ns0gs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-monitor-camera" /></template>
<style>
.f817ns0gs {
  d: path("M9.415 4.853a2.5 2.5 0 1 1-1.768-1.768m10 4.83a2.5 2.5 0 1 1 1.768-1.768M9.25 11.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75 6V21m-4.5 0h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-eja73-n {
  d: path("M5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
