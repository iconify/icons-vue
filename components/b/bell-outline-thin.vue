<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xd3fvew_d"/><path class="n5-apabry"/><path class="k4j9-ccbl"/><path class="ok9ioqb8x"/><path class="k-jt90-vx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-jt90-vx {
  d: path("M11 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.k4j9-ccbl {
  d: path("M18 13v4");
}

.n5-apabry {
  d: path("M6 13v4");
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.xd3fvew_d {
  d: path("M6 13a6 6 0 0 1 12 0");
}

</style>
