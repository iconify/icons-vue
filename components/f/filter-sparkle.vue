<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="zzwtwabgm"/><path class="ttxdcjbnj"/><path class="ieho11bzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:filter-sparkle" /></template>
<style>
.ieho11bzo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 16.25a3.25 3.25 0 0 0 5 0M3.92 3.38l4.16 1.74q.92.38.21 1.09L5.21 9.29q-.71.71-.92-.27L3.21 3.98Q3 3 3.92 3.38m16.16 0l-4.16 1.74q-.92.38-.21 1.09l3.08 3.08q.71.71.92-.27l1.08-5.04q.21-.98-.71-.6");
}

.ttxdcjbnj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 12.75h.01m5.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zzwtwabgm {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
