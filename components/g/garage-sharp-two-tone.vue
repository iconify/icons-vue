<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e6gil1boz"/><path class="h7__bybvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:garage-sharp-two-tone" /></template>
<style>
.e6gil1boz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.66 1.06C11.916 0.967 12.201 0.982 12.447 1.105L22.447 6.105C22.786 6.275 23 6.621 23 7V22C23 22.552 22.552 23 22 23H2C1.448 23 1 22.552 1 22V7C1 6.621 1.214 6.275 1.553 6.105L11.553 1.105L11.66 1.06Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h7__bybvy {
  d: path("M6 22H2V7L12 2L22 7V22H18M18 22V11H6V22M18 22H6M22 7H2M10 18H14");
}

</style>
