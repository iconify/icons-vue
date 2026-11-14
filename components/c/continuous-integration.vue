<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abi02fbuk"/><path class="ryrw1s4gg"/><path class="nh73uxxst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:continuous-integration" /></template>
<style>
.abi02fbuk {
  d: path("M15.75 5.505A7.5 7.5 0 0 1 12 19.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nh73uxxst {
  d: path("M9.75 2.25L12 4.5L9.75 6.75m0 5.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.ryrw1s4gg {
  d: path("M14.25 17.25L12 19.5l2.25 2.25m-6-3.255A7.5 7.5 0 0 1 12 4.5");
}

</style>
