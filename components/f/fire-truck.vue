<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="j_y5cgbra"/><path class="tsq6kqbdc"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-truck" /></template>
<style>
.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_y5cgbra {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8H17.6a1.5 1.5 0 0 1 1.3.75l2.1 3.6c.17.3.25.6.25.9v2.5a1 1 0 0 1-1 1H3.75a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
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

.tsq6kqbdc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 8v4.25H20M3.25 3.5h12.5M3.25 5.75h12.5M6.5 3.5v2.25m3-2.25v2.25m3-2.25v2.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
