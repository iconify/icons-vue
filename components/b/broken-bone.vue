<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qow5sdbep"/><path class="u-yzn_ozs"/><path class="ba1xfz1zc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broken-bone" /></template>
<style>
.ba1xfz1zc {
  d: path("M16.5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-8-7.5L11 11m2 2l2.5 2.5M15 8l2-2M6.5 18l2-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qow5sdbep {
  d: path("M3.5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.u-yzn_ozs {
  d: path("M6 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
