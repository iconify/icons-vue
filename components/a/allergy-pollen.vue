<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="cccdy6fet"/><path class="y0pokobge"/><path class="casxsoblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:allergy-pollen" /></template>
<style>
.casxsoblm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 4h.01M20 12h.01");
}

.cccdy6fet {
  cx: 9.5px;
  cy: 14.25px;
  r: 6.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0pokobge {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 11.25L8 12.5l-1.75 1.25m6.5-2.5L11 12.5l1.75 1.25m-3.25 2a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5m9.63-10.71a1.1 1.1 0 1 1 .55 1.67a1.1 1.1 0 1 1-1.43 1.04a1.1 1.1 0 1 1-1.43-1.04a1.1 1.1 0 1 1 .55-1.67a1.1 1.1 0 1 1 1.76 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
