<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axgbv9c2x"/><path class="mw35lwbbm"/><path class="uq717lsoo"/><path class="t9edcbc3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jigsaw-duotone-regular" /></template>
<style>
.axgbv9c2x {
  fill: currentColor;
  d: path("M3 3h7c0 -1.5 4 -1.5 4 0v7c1.5 0 1.5 4 0 4v7H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mw35lwbbm {
  fill: currentColor;
  d: path("M17 3h4v18h-4v-7c1.5 0 1.5 -4 0 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t9edcbc3d {
  d: path("M17 3h4v18h-4v-7c1.5 0 1.5 -4 0 -4Z");
}

.uq717lsoo {
  d: path("M3 3h7c0 -1.5 4 -1.5 4 0v7c1.5 0 1.5 4 0 4v7H3Z");
}

</style>
