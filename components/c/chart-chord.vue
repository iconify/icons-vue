<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eadps1bth"/><circle class="wmqzadcel"/><circle class="mblugibxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-chord" /></template>
<style>
.eadps1bth {
  d: path("M4.75 4.25h14.5M4.75 12.5h14.5M4.75 4.25v16.5m4.83-16.5V6.8m0 3.2v10.75m4.84-16.5V15m0 3.2v2.55m4.83-16.5v16.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mblugibxw {
  cx: 14.42px;
  cy: 16.6px;
  r: 1.6px;
}

.wmqzadcel {
  cx: 9.58px;
  cy: 8.4px;
  r: 1.6px;
}

</style>
