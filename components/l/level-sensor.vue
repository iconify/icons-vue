<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ifd8vqp9x"/><path class="jwh0v6w7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:level-sensor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifd8vqp9x {
  d: path("M7 5h10a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V8.5A3.5 3.5 0 0 1 7 5m8.5-2.5V16");
}

.jwh0v6w7l {
  d: path("M14 17.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M3.5 12c2.25-1.5 4.25 1.5 6.5 0s4.25 1.5 6.5 0c1.25-.75 2.5-.5 4 0");
}

</style>
