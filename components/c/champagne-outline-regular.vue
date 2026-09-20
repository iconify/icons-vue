<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ytw5afb0h"/><path class="xtjp0b80d"/><path class="frofbtbej"/><path class="dxdpz6gbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:champagne-outline-regular" /></template>
<style>
.dxdpz6gbz {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.frofbtbej {
  d: path("M14 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xtjp0b80d {
  d: path("M6 5V2h4v3");
}

.ytw5afb0h {
  d: path("M5 21v-8c0 -2 1 -3 1 -5V5h4v3c0 2 1 3 1 5v8Z");
}

</style>
