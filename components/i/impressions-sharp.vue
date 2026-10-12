<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b5a9s70ca"/><path class="qzt_3-t-d"/><path class="xup8hnitz"/><path class="zyi9fdcvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:impressions-sharp" /></template>
<style>
.b5a9s70ca {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75h15v15");
}

.qzt_3-t-d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h15v15h-15z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xup8hnitz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 13.75c1-1.75 2.5-2.75 4.5-2.75s3.5 1 4.5 2.75c-1 1.75-2.5 2.75-4.5 2.75s-3.5-1-4.5-2.75Z");
}

.zyi9fdcvr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 13.75h.01");
}

</style>
