<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="qytdm3-3r"/><circle class="d8ctrbbdq"/><circle class="jzpog3btl"/><path class="gc432-bfc"/><circle class="ddcyy1bpr"/><circle class="j6g2i2bnc"/><circle class="tljdjfbpp"/><path class="niwuj-boh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:braille-reading-sharp" /></template>
<style>
.d8ctrbbdq {
  cx: 6px;
  cy: 12px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ddcyy1bpr {
  cx: 18px;
  cy: 6px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gc432-bfc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 12h.01M6 18h.01M10 18h.01");
}

.j6g2i2bnc {
  cx: 14px;
  cy: 12px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzpog3btl {
  cx: 10px;
  cy: 6px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.niwuj-boh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 6h.01M18 12h.01M14 18h.01");
}

.qytdm3-3r {
  cx: 6px;
  cy: 6px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tljdjfbpp {
  cx: 18px;
  cy: 18px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
