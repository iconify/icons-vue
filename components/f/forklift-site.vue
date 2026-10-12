<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ys3jtobsd"/><circle class="sf02ieb1s"/><circle class="r-x-f1bxv"/><path class="mncn-x6_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forklift-site" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mncn-x6_n {
  d: path("M17.5 3.5v14h3.75");
}

.r-x-f1bxv {
  cx: 11.75px;
  cy: 18.75px;
  r: 2.25px;
}

.sf02ieb1s {
  cx: 5.75px;
  cy: 18.75px;
  r: 2.25px;
}

.ys3jtobsd {
  d: path("M3.75 12.5H6V6a1 1 0 0 1 1-1h4.1a1 1 0 0 1 .96.72l2.19 6.78v3a1 1 0 0 1-1 1h-9.5a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1m0 4h9.5");
}

</style>
