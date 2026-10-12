<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="up5bnccaf"/><circle class="jo45v1frk"/><circle class="yohxqabuf"/><circle class="mc82-xb_k"/><path class="dltwjgb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grid-network-sharp" /></template>
<style>
.dltwjgb4m {
  d: path("M7.25 5h9.5M5 7.25v9.5m14-9.5v9.5M7.25 19h9.5M13 8.5L10.5 12h3L11 15.5");
}

.jo45v1frk {
  cx: 19px;
  cy: 5px;
  r: 2.25px;
}

.mc82-xb_k {
  cx: 19px;
  cy: 19px;
  r: 2.25px;
}

.up5bnccaf {
  cx: 5px;
  cy: 5px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yohxqabuf {
  cx: 5px;
  cy: 19px;
  r: 2.25px;
}

</style>
