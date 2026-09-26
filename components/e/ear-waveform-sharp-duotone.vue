<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i-8j_j4ol"/><path class="svs6qkbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ear-waveform-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i-8j_j4ol {
  stroke-opacity: 0.4;
  d: path("M4 10L4 9C4 5.134 7.134 2 11 2C14.866 2 18 5.134 18 9L18 10M11 22L10 22C8.3431 22 7 20.6569 7 19L7 18");
}

.svs6qkbef {
  d: path("M13.5 10L13.5 9C13.5 7.6193 12.3807 6.5 11 6.5C9.6193 6.5 8.5 7.6193 8.5 9L8.5 11L8.5 12M12 14L12 15L12 18L12 19M16 12L16 13L16 20L16 21M20 14L20 15L20 18L20 19");
}

</style>
