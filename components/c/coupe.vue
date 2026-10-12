<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pbh9z8mwz"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coupe" /></template>
<style>
.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0haxibzw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 19h.01");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.pbh9z8mwz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5v-1q0-1.25 1.22-1.54l2.81-.67Q8 12 8.94 11.18l1.87-1.61q.94-.82 2.19-.82h1q1.25 0 2.29.69l3.92 2.62q1.04.69 1.04 1.94v1.5q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25m6.5-3.5h9.25");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
