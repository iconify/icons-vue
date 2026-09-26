<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i477xac4d"/><path class="umyorzjad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cpu-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i477xac4d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20L3 4C3 3.4477 3.4477 3 4 3Z");
  stroke: none;
}

.umyorzjad {
  d: path("M8 8L16 8L16 16L8 16L8 8ZM9 4L9 1M9 20L9 23M4 9L1 9M20 9L23 9M15 4L15 1M15 20L15 23M4 15L1 15M20 15L23 15");
}

</style>
