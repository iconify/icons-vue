<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z_mt8_eln"/><path class="d1cpymbtb"/><rect class="rwp2z_5ju"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:delivery-truck" /></template>
<style>
.d1cpymbtb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 7.5v2.75H18");
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

.rwp2z_5ju {
  width: 5.5px;
  height: 4.5px;
  x: 5.5px;
  y: 8.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 0.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_mt8_eln {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7a1.5 1.5 0 0 1 1.5-1.5h10.6a2 2 0 0 1 1.7.95l2.2 3.55l1.9.95a1 1 0 0 1 .55.9v3.9a1 1 0 0 1-1 1H4.25a1.5 1.5 0 0 1-1.5-1.5Z");
}

</style>
