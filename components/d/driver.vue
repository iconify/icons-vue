<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yaejx3nnc"/><path class="a2heuzb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:driver" /></template>
<style>
.a2heuzb4y {
  d: path("M8.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m0 0h7M12 18v3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yaejx3nnc {
  d: path("M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-5.5 16v-3c0-4 3.75-7 8.5-7s8.5 3 8.5 7v3");
}

</style>
