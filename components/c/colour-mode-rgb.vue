<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="orsm4xbar"/><path class="zdjidk4at"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-mode-rgb" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.orsm4xbar {
  d: path("M5.5 4h13A3.5 3.5 0 0 1 22 7.5v6a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 13.5v-6A3.5 3.5 0 0 1 5.5 4M12 17v3.5m-4 0h8");
}

.zdjidk4at {
  d: path("M6.25 9za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 6.25 9M12 9za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 12 12a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 12 9m5.75 0za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
