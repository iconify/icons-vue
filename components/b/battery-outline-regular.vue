<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mqh2f6n-y"/><path class="om2raabrv"/><path class="eff8y6gxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:battery-outline-regular" /></template>
<style>
.eff8y6gxz {
  d: path("M5 12a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2");
}

.mqh2f6n-y {
  d: path("M2 9a2 2 0 0 1 2 -2h11a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.om2raabrv {
  d: path("M20 10v4");
}

</style>
