<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l4_xfmbwx"/><path class="fdze63beh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:life-endowment" /></template>
<style>
.fdze63beh {
  d: path("M6 15.75a6 2 0 1 0 12 0a6 2 0 1 0-12 0m6-2V9m0 2c0-2.5-2-4.5-4.5-4.5C7.5 9 9.5 11 12 11m0-1.5C12 7 14 5 16.5 5c0 2.5-2 4.5-4.5 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4_xfmbwx {
  d: path("M6 19a6 2 0 1 0 12 0a6 2 0 1 0-12 0");
}

</style>
