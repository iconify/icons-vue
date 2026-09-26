<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x9emg4bdv"/><path class="ffxgx3bcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-up-two-tone" /></template>
<style>
.ffxgx3bcb {
  d: path("M7 15L10.3887 11.1877C10.7342 10.799 11.32 10.74 11.7361 11.0521L14.3361 13.002C14.721 13.2908 15.2571 13.2644 15.6118 12.9392L20.2628 8.6757M16.5 8L20.5 8C20.7761 8 21 8.2239 21 8.5L21 12.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x9emg4bdv {
  stroke-opacity: 0.4;
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21");
}

</style>
