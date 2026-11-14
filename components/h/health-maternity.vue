<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vra3dznrp"/><path class="ggc1sy86n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:health-maternity" /></template>
<style>
.ggc1sy86n {
  d: path("M9 8c0 3.5 1 5.5 4 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vra3dznrp {
  d: path("M7 2.5C7 6 5.5 8.5 5.5 12c0 3 1 5.5 1 9.5H12c0-2 .75-3.5 2-4.5c5.5-1.25 6-7.5.25-7.5c1.75-1 1.5-3.5-.75-4c-1.25-.5-1.75-1.5-1.75-3");
}

</style>
