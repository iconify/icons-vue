<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ju0in2s0f"/><path class="xuz6yn0tm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-sensitive-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ju0in2s0f {
  stroke-opacity: 0.4;
  d: path("M1.9417 19.1631L7 5L12.0583 19.1631M3.7857 14L10.2143 14");
}

.xuz6yn0tm {
  d: path("M22 16C22 17.6569 20.6569 19 19 19C17.3431 19 16 17.6569 16 16C16 14.3431 17.3431 13 19 13C20.6569 13 22 14.3431 22 16ZM22 11L22 20");
}

</style>
