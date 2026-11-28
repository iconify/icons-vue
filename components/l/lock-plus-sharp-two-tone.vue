<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ya9q9z7xi"/><path class="rm9v8qtmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-plus-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rm9v8qtmr {
  d: path("M7.5 10L7.5 6.5C7.5 4.0147 9.5147 2 12 2C14.4853 2 16.5 4.0147 16.5 6.5L16.5 10M4 10L4 22L20 22L20 10L4 10ZM12 13L12 19M9 16L15 16");
}

.ya9q9z7xi {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10C3 9.4477 3.4477 9 4 9L20 9C20.5523 9 21 9.4477 21 10L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22Z");
  stroke: none;
}

</style>
