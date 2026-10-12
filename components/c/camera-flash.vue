<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dtknt5g7a"/><circle class="l0fn-57om"/><path class="ujy3-ns0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camera-flash" /></template>
<style>
.dtknt5g7a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.25a2 2 0 0 1 2-2h2.1l1.1-1.85a1.5 1.5 0 0 1 1.3-.75h4.5a1.5 1.5 0 0 1 1.3.75l1.1 1.85h2.1a2 2 0 0 1 2 2v8.5a2.5 2.5 0 0 1-2.5 2.5H5.75a2.5 2.5 0 0 1-2.5-2.5Z");
}

.l0fn-57om {
  cx: 12px;
  cy: 13.25px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ujy3-ns0y {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 10.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
