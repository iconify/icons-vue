<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cxtpw7b0n"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:convertible" /></template>
<style>
.cxtpw7b0n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.75zq0-1 1.23-1.25l3.79-.75q1.23-.25 2.48-.25h4q1.25 0 1.94-1.04l.12-.17q.69-1.04 1.94-1.04h.25q1.25 0 2 .88q.75.87.75 2.12v1.25q0 1.25-1.25 1.25H4q-1.25 0-1.25-1M9 13.5L11.75 9");
}

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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
