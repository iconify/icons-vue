<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lkk_pnbow"/><circle class="lzanorbmf"/><circle class="dn0bjhepg"/><circle class="bn_m5u55m"/><path class="kkvfp_m1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-mind-blown-sharp" /></template>
<style>
.bn_m5u55m {
  cx: 12px;
  cy: 17.75px;
  r: 1px;
}

.dn0bjhepg {
  cx: 15px;
  cy: 14.75px;
  r: 1px;
}

.kkvfp_m1y {
  d: path("M7.25 9.25a1.9 1.9 0 0 1-.4-3.75a2.75 2.75 0 0 1 5.15-1a2.75 2.75 0 0 1 5.15 1a1.9 1.9 0 0 1-.4 3.75Z");
}

.lkk_pnbow {
  d: path("M5 11.75h15v1.5a8 8 0 0 1-16 0v-1.5z");
}

.lzanorbmf {
  cx: 9px;
  cy: 14.75px;
  r: 1px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
