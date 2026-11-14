<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfcnm_b_w"/><path class="misqej4xi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:absenteeism" /></template>
<style>
.gfcnm_b_w {
  d: path("M4.75 9.75zA1.25 1.25 0 0 1 6 11v3.75A1.25 1.25 0 0 1 4.75 16a1.25 1.25 0 0 1-1.25-1.25V11a1.25 1.25 0 0 1 1.25-1.25M3.5 16h7m-3.25 0v3.5m-3 0h6m4.5-9.75zA1.25 1.25 0 0 1 16 11v3.75A1.25 1.25 0 0 1 14.75 16a1.25 1.25 0 0 1-1.25-1.25V11a1.25 1.25 0 0 1 1.25-1.25M13.5 16h7m-3.25 0v3.5m-3 0h6M3 7l5.5-3.5l4 2.5l7.25-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.misqej4xi {
  d: path("M16 2.5h3.75v3.75");
}

</style>
