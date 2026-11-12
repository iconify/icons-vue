<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="lgpmj5glp"/><circle class="px5xiwqdn"/><path class="ux2n7ervq"/><path class="jlbwv3bdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-2-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlbwv3bdp {
  d: path("M6 21L4.5 19.5M6.5 17.5L8 19");
}

.lgpmj5glp {
  cx: 15px;
  cy: 9px;
  r: 7px;
}

.px5xiwqdn {
  cx: 15px;
  cy: 9px;
  r: 2px;
}

.ux2n7ervq {
  d: path("M3.5 20.5L9.5 14.5");
}

</style>
