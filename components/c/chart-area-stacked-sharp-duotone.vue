<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q75oabbpt"/><path class="ie9sz5k4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-area-stacked-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ie9sz5k4u {
  stroke-opacity: 0.4;
  d: path("M2.6585 12.2988L3 12L10.7143 5.25L14.5714 8.625L21 3L21.2829 2.7525");
}

.q75oabbpt {
  fill: currentColor;
  d: path("M12 22L3 22C2.4477 22 2 21.5523 2 21L2 18.8C2 18.5078 2.1278 18.2301 2.3499 18.0401L10.0642 11.4401C10.2454 11.2852 10.4759 11.2 10.7143 11.2C10.9527 11.2 11.1833 11.2852 11.3644 11.4402L14.5714 14.184L20.3499 9.2401C20.5311 9.0852 20.7616 9 21 9C21.5523 9 22 9.4477 22 10L22 21C22 21.5523 21.5523 22 21 22Z");
  stroke: none;
}

</style>
