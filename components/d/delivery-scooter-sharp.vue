<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="u-qm32bzn"/><circle class="zihitx70r"/><path class="qwnwi886e"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:delivery-scooter-sharp" /></template>
<style>
.pr2iyxt7r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19h.01");
}

.qwnwi886e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 19h.01");
}

.u-qm32bzn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 15.5v-2l.63-.62l.62-.63h7l.4 1.19l.7 2.12l.4 1.19H2.75zm0-8.5h5v5.25h-5zm9.75 9.75h3l2-11.25h-3");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xw30-oz_l {
  cx: 18px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zihitx70r {
  cx: 6.5px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
