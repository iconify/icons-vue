<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ft6muzbym"/><circle class="zihitx70r"/><path class="qwnwi886e"/><circle class="xw30-oz_l"/><path class="pr2iyxt7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cement-mixer-sharp" /></template>
<style>
.ft6muzbym {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.05 10.21a5 3.25-20 1 1 9.4-3.42a5 3.25-20 1 1-9.4 3.42Zm2.14-4.06l2.11 5.79m.9-6.88l2.11 5.79m5.44-2.35h3l.926.001l.414.829l1 2l.159.316l.001.354v2.25h-5.5Zm0 3h5.5m-18.5 2.75h13");
}

.pr2iyxt7r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 19h.01");
}

.qwnwi886e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 19h.01");
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
