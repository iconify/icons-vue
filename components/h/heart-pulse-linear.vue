<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qr3l2kuff"/><path class="z-uaizbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-pulse-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qr3l2kuff {
  d: path("M18 12H17.1986C16.3689 12 15.9541 12 15.6102 12.1947C15.2664 12.3894 15.0529 12.7451 14.6261 13.4565L14.6261 13.4565L14.5952 13.508C14.1976 14.1707 13.9987 14.5021 13.7095 14.4967C13.4202 14.4912 13.2339 14.1526 12.8615 13.4754L11.1742 10.4076C10.8269 9.77618 10.6533 9.46046 10.3759 9.44549C10.0986 9.43052 9.892 9.7257 9.47875 10.3161L9.19573 10.7204L9.19573 10.7204C8.75681 11.3474 8.53734 11.6609 8.21173 11.8305C7.88612 12 7.50342 12 6.73803 12H6");
}

.z-uaizbta {
  stroke-linejoin: round;
  d: path("M2 9.26044C2 13.0079 6.01943 16.9714 8.96173 19.3707C10.2937 20.4569 10.9597 21 12 21C13.0403 21 13.7063 20.4569 15.0383 19.3707C17.9806 16.9714 22 13.008 22 9.2604C22 3.34931 16.4998 0.662637 12 5.49877C7.50016 0.662637 2 3.3495 2 9.26044Z");
}

</style>
