<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="vzo3ypbps"/><path class="x43s2zn6y"/><path class="pfllnjb4h"/><path class="dul6eto5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-sleep-linear" /></template>
<style>
.dul6eto5z {
  stroke-linejoin: round;
  d: path("M9 10H15L9 16H15");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfllnjb4h {
  stroke-linejoin: round;
  d: path("M20.5 4.5L16.5 2");
}

.vzo3ypbps {
  cx: 12px;
  cy: 13px;
  r: 9px;
}

.x43s2zn6y {
  stroke-linejoin: round;
  d: path("M3.5 4.5L7.50002 2");
}

</style>
