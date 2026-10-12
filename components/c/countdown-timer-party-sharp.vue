<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="n-ir9pvha"/><circle class="xcc9ljb_q"/><path class="nis2u2esd"/><path class="aat8naczl"/><path class="s-d-apyna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:countdown-timer-party-sharp" /></template>
<style>
.aat8naczl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 18.25h.01m-4.51-4.5h.01m8.99 0h.01");
}

.n-ir9pvha {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 2.75h3.5m-1.75 0V6.5");
}

.nis2u2esd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 13.75v-4.5m0 4.5l3 1.75");
}

.s-d-apyna {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.25 5l.85-1.6m1.4 3.85l1.75-.6m-.5 4.1l1.5.6m-1.5-8.6l.25 1.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xcc9ljb_q {
  cx: 11px;
  cy: 13.75px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
