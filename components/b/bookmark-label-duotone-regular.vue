<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fbde_z08y"/><path class="kks1a6bkc"/><path class="w3hyiobto"/><path class="g4pfarntv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bookmark-label-duotone-regular" /></template>
<style>
.fbde_z08y {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g4pfarntv {
  d: path("M10 10.5h4v6l-2 -2 -2 2Z");
}

.kks1a6bkc {
  fill: currentColor;
  d: path("M10 10.5h4v6l-2 -2 -2 2Z");
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

.w3hyiobto {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

</style>
