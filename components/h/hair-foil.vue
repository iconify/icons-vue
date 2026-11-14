<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6-kd1qug"/><path class="x_dyaiaqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hair-foil" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6-kd1qug {
  d: path("M5.25 4.5h13.5a1.75 1.75 0 0 1 1.75 1.75v13.5a1.75 1.75 0 0 1-1.75 1.75h-8.025a1.75 1.75 0 0 1-1.238-.513l-5.474-5.474a1.75 1.75 0 0 1-.513-1.238V6.25A1.75 1.75 0 0 1 5.25 4.5");
}

.x_dyaiaqp {
  d: path("m3.5 15l5.75.75l.75 5.75m2-19C9 6 16 8 13 12c-2.5 3 1 5 .5 7m3-16.5c-3 3.5 3 5.5.5 9.5");
}

</style>
