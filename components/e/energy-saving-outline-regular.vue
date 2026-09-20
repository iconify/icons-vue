<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zo_xbmb4y"/><path class="g-g566bva"/><path class="eob2zbc5p"/><path class="vqwutobjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:energy-saving-outline-regular" /></template>
<style>
.eob2zbc5p {
  d: path("M9 19h6");
}

.g-g566bva {
  d: path("M8 10v6h8v-6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vqwutobjj {
  d: path("M9 13c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.zo_xbmb4y {
  d: path("M6 10a6 6 0 0 1 12 0");
}

</style>
