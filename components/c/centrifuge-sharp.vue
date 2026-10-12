<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qk2fjnsuh"/><circle class="lcc5z2bbq"/><path class="cjbbvacfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:centrifuge-sharp" /></template>
<style>
.cjbbvacfn {
  d: path("M17.16 5.38a9 9 0 0 1 3.81 6.59");
}

.lcc5z2bbq {
  cx: 12px;
  cy: 12.75px;
  r: 1.75px;
}

.qk2fjnsuh {
  d: path("M13.5 6V2.75h-3V7.5h3zm3.6 11.42l1.51.88a1.5 1.5 0 0 0 1.5-2.6l-1.51-.87l-1.343-.66l-1.5 2.59zM5.4 14.83l-1.51.87a1.5 1.5 0 0 0 1.5 2.6l1.51-.88l1.241-.837l-1.5-2.59z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
