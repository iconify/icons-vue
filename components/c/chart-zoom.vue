<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="n6dwwqesf"/><path class="dqxgvlapa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-zoom" /></template>
<style>
.dqxgvlapa {
  d: path("m15.75 15.75l5.5 5.5m-14.5-8.5L9.25 10l2 1.75l3.25-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n6dwwqesf {
  cx: 10.5px;
  cy: 10.5px;
  r: 7.25px;
}

</style>
