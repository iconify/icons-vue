<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="igfd9jstm"/><path class="dm4ais44r"/><circle class="n67838b6u"/><circle class="pilcef9lb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mail-cart-sharp" /></template>
<style>
.dm4ais44r {
  d: path("m9.75 4.75l2.75 2l2.75-2m-10 4h14.5v7.5H5.25zm0 2H3V6m5.25 10.25v2.5m8.5-2.5v2.5");
}

.igfd9jstm {
  d: path("M8.75 3.75h7.5v5h-7.5z");
}

.n67838b6u {
  cx: 8.25px;
  cy: 20px;
  r: 1.25px;
}

.pilcef9lb {
  cx: 16.75px;
  cy: 20px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
