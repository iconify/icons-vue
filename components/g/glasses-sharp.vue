<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ysextzbnj"/><circle class="usm9rcbjq"/><path class="l8wjdebrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glasses-sharp" /></template>
<style>
.l8wjdebrg {
  d: path("M10.25 13.75L12 12.557l1.75 1.193M3 13.25L5 6.5h1.5M21 13.25L19 6.5h-1.5");
}

.usm9rcbjq {
  cx: 17.5px;
  cy: 14.5px;
  r: 3.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ysextzbnj {
  cx: 6.5px;
  cy: 14.5px;
  r: 3.75px;
}

</style>
