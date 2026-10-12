<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gfm5tib1v"/><path class="bn93zzols"/><path class="qjigr-bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:band-aid" /></template>
<style>
.bn93zzols {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.88 12L12 9.88a.75.75 0 0 1 1.06 0l1.06 1.06a.75.75 0 0 1 0 1.06L12 14.12a.75.75 0 0 1-1.06 0l-1.06-1.06a.75.75 0 0 1 0-1.06");
}

.gfm5tib1v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.93 13.41l8.48-8.48a4 4 0 0 1 5.66 5.66l-8.48 8.48a4 4 0 0 1-5.66-5.66");
}

.qjigr-bze {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.24 7.76h.01m-8.49 8.48h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
