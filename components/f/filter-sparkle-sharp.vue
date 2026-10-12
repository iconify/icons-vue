<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="zzwtwabgm"/><path class="ttxdcjbnj"/><path class="wralvr49w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:filter-sparkle-sharp" /></template>
<style>
.ttxdcjbnj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 12.75h.01m5.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wralvr49w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 16.25l2.5 3.01l2.5-3.01M3.92 3.38l4.16 1.74l.92.38l-.71.71l-3.08 3.08l-.71.71l-.21-.98l-1.08-5.04L3 3zm16.16 0l-4.16 1.74l-.92.38l.71.71l3.08 3.08l.71.71l.21-.98l1.08-5.04L21 3z");
}

.zzwtwabgm {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
