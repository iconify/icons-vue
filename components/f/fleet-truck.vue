<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="lcas9y73a"/><rect class="p6kdcim6e"/><path class="evqi91vjn"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fleet-truck" /></template>
<style>
.evqi91vjn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 16.75V11a1 1 0 0 1 1-1h1.1a1.5 1.5 0 0 1 1.25.67l1.15 1.73a1.5 1.5 0 0 1 .25.83v3.52Z");
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

.lcas9y73a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.25v-1a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v3.5");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.p6kdcim6e {
  width: 11.25px;
  height: 9.25px;
  x: 2.75px;
  y: 7.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
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
