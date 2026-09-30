<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="eoe-mjedz"/><path class="n3ys2_2uz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:landmark-sharp-two-tone" /></template>
<style>
.eoe-mjedz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 9L21 9C21.5524 9.0002 22.0002 8.5524 22.0002 8.0001C22.0002 7.6368 21.8032 7.3022 21.4856 7.1258L12.4856 2.1258C12.3371 2.0433 12.1699 2 12 2C11.8301 2 11.6629 2.0433 11.5144 2.1258L2.5144 7.1258C2.1968 7.3022 1.9998 7.6368 1.9998 8.0001C1.9998 8.5524 2.4476 9.0002 3 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n3ys2_2uz {
  d: path("M3 8L21 8L12 3L3 8ZM6 11L6 18M12 11L12 18M18 11L18 18M2 21L22 21");
}

</style>
