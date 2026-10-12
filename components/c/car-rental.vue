<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="u1ka-bspc"/><path class="cmxeeyubs"/><path class="onefqzb1e"/><circle class="skd8m5b2v"/><path class="crokb0b7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-rental" /></template>
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

.u1ka-bspc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.75 9l1.3-3.6A2 2 0 0 1 8.95 4h6.1a2 2 0 0 1 1.9 1.4l1.3 3.6m-7 6.5H5a2 2 0 0 1-2-2V11a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v1.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
