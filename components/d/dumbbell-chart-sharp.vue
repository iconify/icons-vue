<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v-u8c7bqs"/><path class="cbl8z-2kh"/><circle class="mllx8p2ek"/><circle class="iz4a2nbcp"/><path class="kmhj5z3xv"/><circle class="q7oluabpb"/><circle class="uqhsgzn0r"/><path class="dbug20bfo"/><circle class="yrmd442fu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dumbbell-chart-sharp" /></template>
<style>
.cbl8z-2kh {
  d: path("M7 5.75h6");
}

.dbug20bfo {
  d: path("M6.75 18.25h3.75");
}

.iz4a2nbcp {
  cx: 8.5px;
  cy: 12px;
  r: 2px;
}

.kmhj5z3xv {
  d: path("M10.5 12h6.75");
}

.mllx8p2ek {
  cx: 15px;
  cy: 5.75px;
  r: 2px;
}

.q7oluabpb {
  cx: 19.25px;
  cy: 12px;
  r: 2px;
}

.uqhsgzn0r {
  cx: 4.75px;
  cy: 18.25px;
  r: 2px;
}

.v-u8c7bqs {
  cx: 5px;
  cy: 5.75px;
  r: 2px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrmd442fu {
  cx: 12.5px;
  cy: 18.25px;
  r: 2px;
}

</style>
