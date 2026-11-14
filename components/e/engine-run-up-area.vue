<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy0g6pbvi"/><path class="gohp-6a8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:engine-run-up-area" /></template>
<style>
.gohp-6a8d {
  d: path("M6.5 7.75h8l3.5 2.5v3.5l-3.5 2.5h-8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy0g6pbvi {
  d: path("M2.5 7V2.5H7m10 0h4.5V7m0 10v4.5H17m-10 0H2.5V17m2-5a2 4.25 0 1 0 4 0a2 4.25 0 1 0-4 0");
}

</style>
