<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="upb39q7rv"/><path class="nbe05sb8d"/><circle class="l30f8ka2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fever-face-sharp" /></template>
<style>
.l30f8ka2b {
  cx: 12.25px;
  cy: 15.75px;
  r: 1.5px;
}

.nbe05sb8d {
  d: path("m6.75 10.25l1 1l1-1m3 0l1 1l1-1m-.44 4.44L20.5 7.5");
}

.upb39q7rv {
  cx: 10.5px;
  cy: 12.75px;
  r: 7.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
