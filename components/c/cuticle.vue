<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dknz0ej_k"/><path class="unn-zh7kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cuticle" /></template>
<style>
.dknz0ej_k {
  d: path("M5.5 21.5V9a6.5 6.5 0 0 1 13 0v12.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unn-zh7kf {
  d: path("M8.5 9.5a3.5 3.5 0 0 1 7 0V15q-3.5 2.5-7 0Zm0 8.5q3.5 3.5 7 0");
}

</style>
