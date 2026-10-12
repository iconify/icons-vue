<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tdx612tmg"/><path class="tgvx7xb2z"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dump-truck" /></template>
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

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tdx612tmg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5v-.25Q2.75 14 4 14h9.25q1.25 0 1.25-1.25V11q0-1.25 1.25-1.25h1.5q1.25 0 2.09.92l1.07 1.16q.84.92.84 2.17v1.5q0 1.25-1.25 1.25H4q-1.25 0-1.25-1.25");
}

.tgvx7xb2z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.55 10.73l-7.1-2.71q-.7-.27-.43-.97l.81-2.1q.27-.7.97-.43l7.1 2.71q.7.27.43.97l-.81 2.1q-.27.7-.97.43");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
