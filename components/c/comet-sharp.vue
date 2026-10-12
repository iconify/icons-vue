<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="aeip39b0i"/><path class="afqmklkxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:comet-sharp" /></template>
<style>
.aeip39b0i {
  cx: 16px;
  cy: 8px;
  r: 4.25px;
}

.afqmklkxw {
  d: path("m3.75 20.25l7.5-7.5m-2 7.5L14.5 15m-10.75-.25L9 9.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
