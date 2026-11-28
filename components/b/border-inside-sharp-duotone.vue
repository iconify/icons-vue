<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fl6e6_oav"/><path class="n2mv93pmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:border-inside-sharp-duotone" /></template>
<style>
.fl6e6_oav {
  stroke-opacity: 0.4;
  d: path("M3 7L3 3L7 3M17 3L21 3L21 7M21 17L21 21L17 21M7 21L3 21L3 17");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n2mv93pmz {
  d: path("M9.5 3L14.5 3M21 9.5L21 14.5M14.5 21L9.5 21M3 14.5L3 9.5M12 3L12 21M3 12L21 12");
}

</style>
