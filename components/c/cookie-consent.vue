<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vh_u1xsdm"/><path class="ccxihmb4f"/><circle class="jhfl8tb7m"/><path class="atnwavvpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cookie-consent" /></template>
<style>
.atnwavvpg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16 17.5l1 1l1.9-2");
}

.ccxihmb4f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 8h.01m4.74-1.25h.01m-5.26 6h.01m3.99-1.5h.01");
}

.jhfl8tb7m {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vh_u1xsdm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.54 18.18a7.75 7.75 0 1 1 6.64-6.64a6 6 0 0 0-6.64 6.64");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
