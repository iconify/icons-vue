<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4bkjb_rz"/><path class="fptai0b8y"/><path class="nig5p9ige"/><path class="fcn0q-bsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:discount-student" /></template>
<style>
.fcn0q-bsv {
  d: path("M17.26 14.25h2.99a1.5 1.5 0 0 1 1.5 1.5v4.5a1.5 1.5 0 0 1-1.5 1.5h-2.99a1.5 1.5 0 0 1-1.209-.613l-1.65-2.25a1.5 1.5 0 0 1 0-1.774l1.65-2.25a1.5 1.5 0 0 1 1.209-.613M16.75 18h.01");
}

.fptai0b8y {
  d: path("M11.25 7H4.5v5.75");
}

.g4bkjb_rz {
  d: path("m11.921 3.085l5.146 2.573a1.5 1.5 0 0 1 0 2.684l-5.146 2.573a1.5 1.5 0 0 1-1.342 0L5.433 8.342a1.5 1.5 0 0 1 0-2.684l5.146-2.573a1.5 1.5 0 0 1 1.342 0M6.75 9.25v3.25c1.257 1.257 4.449 1.611 6.796 1.062m2.204-1.891V9.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nig5p9ige {
  fill: currentColor;
  d: path("M4.5 12.75za.75.75 0 0 1 .75.75v.5a.75.75 0 0 1-.75.75a.75.75 0 0 1-.75-.75v-.5a.75.75 0 0 1 .75-.75");
}

</style>
