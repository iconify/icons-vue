<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k0u_xl_dw"/><path class="h3siy4w6z"/><path class="sgr_j7bvk"/><path class="yazo7scbq"/><path class="fmlaifbpn"/><path class="ffwaozrbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:injection-duotone-thin" /></template>
<style>
.ffwaozrbk {
  d: path("M10 10h4");
}

.fmlaifbpn {
  d: path("M12 16v4");
}

.h3siy4w6z {
  d: path("M8 8a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0u_xl_dw {
  fill: currentColor;
  d: path("M8 8a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sgr_j7bvk {
  d: path("M8 3h8");
}

.yazo7scbq {
  d: path("M12 3v3");
}

</style>
