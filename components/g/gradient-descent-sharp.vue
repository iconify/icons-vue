<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pkg4a5bjz"/><path class="vrdw_--oh"/><circle class="xuqu7-bnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gradient-descent-sharp" /></template>
<style>
.pkg4a5bjz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.75c2 9.75 5 15 9 15s7-5.25 9-15");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vrdw_--oh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 9.5h.01m1.99 3.25h.01");
}

.xuqu7-bnz {
  cx: 12px;
  cy: 14.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
