<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="apq5eeq9z"/><path class="rutulxlvn"/><path class="hxua64xnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:atlas-outline-thin" /></template>
<style>
.apq5eeq9z {
  d: path("M9 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxua64xnl {
  d: path("M14 17a5 5 0 0 1 0 -10");
}

.rutulxlvn {
  d: path("M14 7v10");
}

.wuvisubmw {
  d: path("M8 3v18");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
