<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qe1tygbnm"/><path class="ssflydbls"/><path class="o3z3j5btx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boarding-gate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o3z3j5btx {
  d: path("M8.75 16.25H15m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

.qe1tygbnm {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.ssflydbls {
  d: path("M6.25 5.25h4.5m3 0h4m-12.5 16v-10h13.5v10");
}

</style>
