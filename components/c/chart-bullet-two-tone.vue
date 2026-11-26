<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mtky-h3gd"/><path class="x9emg4bdv"/><path class="xlcd6ok1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bullet-two-tone" /></template>
<style>
.mtky-h3gd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 9L20 9C21.1046 9 22 9.8954 22 11L22 13C22 14.1046 21.1046 15 20 15L8 15C6.8954 15 6 14.1046 6 13L6 11C6 9.8954 6.8954 9 8 9Z");
  stroke: none;
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

.xlcd6ok1s {
  d: path("M8 10L20 10C20.5523 10 21 10.4477 21 11L21 13C21 13.5523 20.5523 14 20 14L8 14C7.4477 14 7 13.5523 7 13L7 11C7 10.4477 7.4477 10 8 10ZM16 7V17");
}

</style>
