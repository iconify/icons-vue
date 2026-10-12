<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cxl-ivgoh"/><circle class="e3ijufb_j"/><circle class="dmb4gdc-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:auto-rickshaw" /></template>
<style>
.cxl-ivgoh {
  d: path("M20.5 14.5v-7q0-3.25-3.25-3.25h-7.5q-2.25 0-3 2l-1.25 4H4.25q-1 0-1 1v3.25Z");
}

.dmb4gdc-s {
  cx: 17.5px;
  cy: 19.25px;
  r: 1.75px;
}

.e3ijufb_j {
  cx: 5.5px;
  cy: 19.25px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
