<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yw9ih47nn"/><path class="sbpc9j3vb"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crypto-market" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.sbpc9j3vb {
  d: path("M8 9.5v2m-1.5 0h3V16h-3ZM8 16v1.5M13 4v2m-1.5 0h3v5.5h-3Zm0 0Zm1.5 5.5v2m1 4.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.yw9ih47nn {
  d: path("M3.5 3v17.5h8.3");
}

</style>
