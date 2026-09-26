<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="knf9qebnr"/><path class="psxymtgnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-vertical-end-two-tone" /></template>
<style>
.knf9qebnr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 10L19 10C20.65685 10 22 11.34315 22 13L22 19C22 20.65685 20.65685 22 19 22L5 22C3.34315 22 2 20.65685 2 19L2 13C2 11.34315 3.34315 10 5 10Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.psxymtgnv {
  d: path("M5 11L19 11C20.10457 11 21 11.89543 21 13L21 19C21 20.10457 20.10457 21 19 21L5 21C3.89543 21 3 20.10457 3 19L3 13C3 11.89543 3.89543 11 5 11ZM5 7H19M7 3H17");
}

</style>
