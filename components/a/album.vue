<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fdv8d9b5v"/><circle class="nglvqxg_z"/><circle class="t8cbi0y5r"/><path class="g7re9y2wz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:album" /></template>
<style>
.fdv8d9b5v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.75H4.75a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h1.5A9.25 9.25 0 0 1 10 4.97Z");
}

.g7re9y2wz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 12.75h.01");
}

.nglvqxg_z {
  cx: 15px;
  cy: 12.75px;
  r: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t8cbi0y5r {
  cx: 15px;
  cy: 12.75px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
