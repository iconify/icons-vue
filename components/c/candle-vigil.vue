<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kydufpbwj"/><path class="px-qpsbyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:candle-vigil" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kydufpbwj {
  d: path("M5 3.5V16a5 5 0 0 0 5 5h4a5 5 0 0 0 5-5V3.5");
}

.px-qpsbyz {
  d: path("M10.75 13h2.5A1.75 1.75 0 0 1 15 14.75v1.75a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 9 16.5v-1.75A1.75 1.75 0 0 1 10.75 13M12 6c1.75 1.75 2 3 0 4c-2-1-1.75-2.25 0-4");
}

</style>
