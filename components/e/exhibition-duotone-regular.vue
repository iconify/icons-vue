<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p79r69bcs"/><path class="qqm3sm-he"/><path class="w35n61kja"/><path class="ddr0zpdgr"/><path class="uih_zvhtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:exhibition-duotone-regular" /></template>
<style>
.ddr0zpdgr {
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p79r69bcs {
  fill: currentColor;
  d: path("M8 12h8v6H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qqm3sm-he {
  fill: currentColor;
  d: path("M8 6a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uih_zvhtv {
  d: path("M4 21h16");
}

.w35n61kja {
  d: path("M8 12h8v6H8Z");
}

</style>
