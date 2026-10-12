<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="f7j3o7bme"/><path class="tsq6kqbdc"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire-truck-sharp" /></template>
<style>
.f7j3o7bme {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8H17.6l.867-.001l.433.751l2.1 3.6l.25.441v3.959H2.75V8z");
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

.tsq6kqbdc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 8v4.25H20M3.25 3.5h12.5M3.25 5.75h12.5M6.5 3.5v2.25m3-2.25v2.25m3-2.25v2.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
