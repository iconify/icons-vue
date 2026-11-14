<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j8rsdlcct"/><path class="r2_oy0arb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amber-resin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8rsdlcct {
  d: path("M4 3h16m-8 0c-2.5 4-6 8-6 11.5a6 6 0 0 0 12 0C18 11 14.5 7 12 3");
}

.r2_oy0arb {
  d: path("M9 16q0-2.5 1.75-4");
}

</style>
