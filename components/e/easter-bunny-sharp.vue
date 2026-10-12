<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="eje1mqb8w"/><circle class="lreqg6b4y"/><path class="i17hk1ghw"/><path class="wbpcize8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:easter-bunny-sharp" /></template>
<style>
.eje1mqb8w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 2.75l1 3.5m4-3.5l-1 3.5");
}

.i17hk1ghw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 9.75h.01m2.99 0h.01");
}

.lreqg6b4y {
  cx: 12px;
  cy: 9.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wbpcize8l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.75 16.25a7.75 5 0 0 1-15.5 0l1.94 1.5l1.94-1.5l1.94 1.5l1.94-1.5l1.94 1.5l1.94-1.5l1.94 1.5Z");
}

</style>
