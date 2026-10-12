<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g6ctus9qt"/><path class="khrk6vbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bibliography" /></template>
<style>
.g6ctus9qt {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.khrk6vbyy {
  d: path("M7.75 5.75h-1v3.5h1m2.5-3.5h1v3.5h-1m-2.5 3.25h-1V16h1m2.5-3.5h1V16h-1m4-8.5h3m-3 3.25h2m-2 3.5h3m-3 3.25h2");
}

</style>
