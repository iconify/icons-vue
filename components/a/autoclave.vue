<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="rp1ueqbvi"/><path class="h78pue50n"/><circle class="x6r1rg4bu"/><path class="byty_cczq"/><path class="axvnh-z7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:autoclave" /></template>
<style>
.axvnh-z7j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 10h2m-2 2.75h2M6 19.5v1.75m12-1.75v1.75");
}

.byty_cczq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 6.5h.01");
}

.h78pue50n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6a5.5 5.5 0 1 1 0 11a5.5 5.5 0 1 1 0-11m0 0v2.5m0 6V17M5 11.5h2.5m6 0H16");
}

.rp1ueqbvi {
  width: 18.5px;
  height: 16.25px;
  x: 2.75px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.x6r1rg4bu {
  cx: 10.5px;
  cy: 11.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
