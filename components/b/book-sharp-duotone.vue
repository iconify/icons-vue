<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y2k4xsnap"/><path class="scnqn-bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:book-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.scnqn-bjs {
  d: path("M3 18L4 18L20 18L21 18M8 6L8 14");
}

.y2k4xsnap {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 1L20 1C20.5523 1 21 1.4477 21 2L21 18C21 18.4327 20.8596 18.8538 20.6 19.2C20.5351 19.2865 20.5 19.3918 20.5 19.5C20.5 19.6082 20.5351 19.7135 20.6 19.8C20.8596 20.1462 21 20.5673 21 21L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 2C3 1.4477 3.4477 1 4 1Z");
  stroke: none;
}

</style>
