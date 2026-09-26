<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ol3golbcs"/><path class="rjbgo_b2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-connection-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ol3golbcs {
  d: path("M6 8L6 18L12 18M12 6L18 6L18 16");
}

.rjbgo_b2s {
  fill: currentColor;
  d: path("M18 14C15.9289 14 14 15.9289 14 18C14 20.0711 15.9289 22 18 22C20.0711 22 22 20.0711 22 18C22 15.9289 20.0711 14 18 14ZM3 2L9 2C9.5523 2 10 2.4477 10 3L10 9C10 9.5523 9.5523 10 9 10L3 10C2.4477 10 2 9.5523 2 9L2 3C2 2.4477 2.4477 2 3 2Z");
  stroke: none;
}

</style>
