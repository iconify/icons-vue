<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qkqlybmds"/><path class="ep56mwbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-horizontal-end-two-tone" /></template>
<style>
.ep56mwbtv {
  d: path("M13 3L19 3C20.10457 3 21 3.89543 21 5L21 19C21 20.10457 20.10457 21 19 21L13 21C11.89543 21 11 20.10457 11 19L11 5C11 3.89543 11.89543 3 13 3ZM7 5V19M3 7V17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qkqlybmds {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2L19 2C20.65685 2 22 3.34315 22 5L22 19C22 20.65685 20.65685 22 19 22L13 22C11.34315 22 10 20.65685 10 19L10 5C10 3.34315 11.34315 2 13 2Z");
  stroke: none;
}

</style>
