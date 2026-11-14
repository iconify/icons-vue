<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-j27uk3t"/><path class="kcr6u8b4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cdn" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kcr6u8b4v {
  d: path("M9.5 12a2.5 6.25 0 1 0 5 0a2.5 6.25 0 1 0-5 0M4 2.5zA1.5 1.5 0 0 1 5.5 4A1.5 1.5 0 0 1 4 5.5A1.5 1.5 0 0 1 2.5 4A1.5 1.5 0 0 1 4 2.5m16 0zA1.5 1.5 0 0 1 21.5 4A1.5 1.5 0 0 1 20 5.5A1.5 1.5 0 0 1 18.5 4A1.5 1.5 0 0 1 20 2.5m-16 16zA1.5 1.5 0 0 1 5.5 20A1.5 1.5 0 0 1 4 21.5A1.5 1.5 0 0 1 2.5 20A1.5 1.5 0 0 1 4 18.5m16 0za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

.n-j27uk3t {
  d: path("M5.75 12a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0");
}

</style>
