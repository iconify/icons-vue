<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mddf2e97q"/><path class="ub4bqmegw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beard-goatee" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mddf2e97q {
  d: path("M4.5 3v6.5c0 3 2 5.5 4.5 6.5l3 5l3-5c2.5-1 4.5-3.5 4.5-6.5V3M9 16h6");
}

.ub4bqmegw {
  d: path("M9.5 11.5q2.5 1.5 5 0");
}

</style>
