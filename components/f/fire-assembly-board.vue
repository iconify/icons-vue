<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="txvwndb7o"/><path class="pihzc4y_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-assembly-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pihzc4y_m {
  d: path("M12 5.5c2.25 2 3 3.5 3 4.75a3 3 0 0 1-6 0C9 9 9.75 7.5 12 5.5");
}

.txvwndb7o {
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v6.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 12.5V6a3.5 3.5 0 0 1 3.5-3.5M12 16v5.5m-3.5 0h7");
}

</style>
