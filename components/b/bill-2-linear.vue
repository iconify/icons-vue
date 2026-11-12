<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pvep1hbek"/><path class="hh_iruycs"/><path class="ok10udbbc"/><path class="vhlnnlb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-2-linear" /></template>
<style>
.hh_iruycs {
  d: path("M4 2H20V12.27C20 13.6091 20 14.2787 19.7319 14.8691C19.4638 15.4595 18.9595 15.9004 17.951 16.7822L15.951 18.5309C14.0685 20.177 13.1272 21 12 21C10.8728 21 9.93152 20.177 8.04897 18.5309L6.04897 16.7822C5.04046 15.9004 4.5362 15.4595 4.2681 14.8691C4 14.2787 4 13.6091 4 12.27V2Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ok10udbbc {
  d: path("M8.5 13L15.5 13");
}

.pvep1hbek {
  d: path("M2 2H22");
}

.vhlnnlb3x {
  d: path("M8.5 8L15.5 8");
}

</style>
