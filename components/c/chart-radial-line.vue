<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zr_x0y7qn"/><path class="od_ijqbyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-radial-line" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.od_ijqbyo {
  d: path("m13.011 7.098l2.439 3.252a1.5 1.5 0 0 1 .3.9v3.552a1.5 1.5 0 0 1-2.047 1.397l-3.284-1.285a1.5 1.5 0 0 1-.679-.532l-1.992-2.823a1.5 1.5 0 0 1 .192-1.952l2.838-2.696a1.5 1.5 0 0 1 2.233.187");
}

.zr_x0y7qn {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0m9 0V5.75M12 12l6-2m-6 2l3.75 5M12 12l-3.75 5M12 12l-6-2");
}

</style>
