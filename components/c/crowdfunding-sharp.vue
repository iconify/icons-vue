<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="mx0ir3bdi"/><path class="le45whbbj"/><circle class="clm4m9vec"/><circle class="fxb6qsbdu"/><circle class="h9gbjwb4c"/><path class="m-pbxlbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crowdfunding-sharp" /></template>
<style>
.clm4m9vec {
  cx: 4.75px;
  cy: 15.25px;
  r: 1.5px;
}

.fxb6qsbdu {
  cx: 12px;
  cy: 15.25px;
  r: 1.5px;
}

.h9gbjwb4c {
  cx: 19.25px;
  cy: 15.25px;
  r: 1.5px;
}

.le45whbbj {
  d: path("m13.13 5.77l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

.m-pbxlbqb {
  d: path("M2.75 21.25a2 1.5 0 0 1 4 0m3.25 0a2 1.5 0 0 1 4 0m3.25 0a2 1.5 0 0 1 4 0");
}

.mx0ir3bdi {
  cx: 12px;
  cy: 6.75px;
  r: 4px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
