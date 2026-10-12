<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zism7cb1c"/><path class="cmxeeyubs"/><path class="onefqzb1e"/><circle class="skd8m5b2v"/><path class="crokb0b7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-rental-sharp" /></template>
<style>
.cmxeeyubs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 12.25h.01");
}

.crokb0b7i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 18.75H21v2m-2.75-2v1.75");
}

.onefqzb1e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 15.5V18");
}

.skd8m5b2v {
  cx: 15px;
  cy: 18.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zism7cb1c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 9l1.3-3.6l.438-1.394L8.95 4h6.1l1.462.006l.438 1.394l1.3 3.6m-7 6.5H3V9h18v3.25");
}

</style>
