<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mp1f0_bly"/><path class="jo3duhbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:banjo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo3duhbmt {
  d: path("M11.75 10.25L17 5l1.25-2.5l3.25 3.25L19 7l-5.25 5.25M6 15.5L8.5 18");
}

.mp1f0_bly {
  d: path("M2.5 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>
