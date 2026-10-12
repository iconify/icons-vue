<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mb4tuyzay"/><path class="ge62a6brj"/><circle class="kvb7u3b8m"/><path class="szcjpcvwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:delegation-sharp" /></template>
<style>
.ge62a6brj {
  d: path("M3.5 21.25h6.75v-.75c0-3.2-1.75-5.75-3.75-5.75S2.75 17.3 2.75 20.5v.75zM9 4h9v5m-2-2l2 2l2-2");
}

.kvb7u3b8m {
  cx: 18px;
  cy: 13.75px;
  r: 1.75px;
}

.mb4tuyzay {
  cx: 6.5px;
  cy: 9px;
  r: 2.75px;
}

.szcjpcvwj {
  d: path("M15.5 21.25H21v-.5C21 19.1 19.65 18 18 18s-3 1.1-3 2.75v.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
