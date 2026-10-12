<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bskbyqcvb"/><circle class="lpc-cw7ln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hills" /></template>
<style>
.bskbyqcvb {
  d: path("M2.75 21.25v-3.5c2.5-2.5 5-3.75 8-3.75c3.5 0 6.75 1.75 10.5 5.5v1.75Zm5.5-8.75c2-1.75 4.25-2.75 6.75-2.75s4.5.75 6.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpc-cw7ln {
  cx: 17.75px;
  cy: 5.25px;
  r: 1.75px;
}

</style>
