<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jhxi-trnl"/><path class="frbd75bvy"/><rect class="vjqdasbcf"/><path class="xln_ribbf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ludo-board" /></template>
<style>
.frbd75bvy {
  d: path("M5.75 6.75a1 1 0 0 1 1-1h2.5a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1Zm8 0a1 1 0 0 1 1-1h2.5a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1Zm-8 8a1 1 0 0 1 1-1h2.5a1 1 0 0 1 1 1v2.5a1 1 0 0 1-1 1h-2.5a1 1 0 0 1-1-1Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhxi-trnl {
  width: 18px;
  height: 18px;
  x: 3px;
  y: 3px;
  rx: 2px;
}

.vjqdasbcf {
  width: 4px;
  height: 4px;
  x: 14.25px;
  y: 14.25px;
  rx: 1px;
}

.xln_ribbf {
  d: path("m12 10.6l1.4 1.4l-1.4 1.4l-1.4-1.4Z");
}

</style>
