<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xhojlqdsj"/><path class="q_965sbsc"/><path class="le-ahcccc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:copper-wire-coil" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.le-ahcccc {
  d: path("M8.5 11a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0m10.25 5L21 20");
}

.q_965sbsc {
  d: path("M5.5 11a6.5 4.25 0 1 0 13 0a6.5 4.25 0 1 0-13 0");
}

.xhojlqdsj {
  d: path("M2.5 11a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0");
}

</style>
