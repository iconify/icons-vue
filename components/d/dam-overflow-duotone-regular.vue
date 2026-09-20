<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oji3pvsxe"/><path class="me0af_bhu"/><path class="npv4e-b7s"/><path class="nvnpnwbdj"/><path class="e0ead5bmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dam-overflow-duotone-regular" /></template>
<style>
.e0ead5bmw {
  d: path("M3 12h3");
}

.me0af_bhu {
  d: path("M6 4h4v16H6Z");
}

.npv4e-b7s {
  d: path("M10 8h4l4 4v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvnpnwbdj {
  d: path("M3 8h3");
}

.oji3pvsxe {
  fill: currentColor;
  d: path("M6 4h4v16H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
