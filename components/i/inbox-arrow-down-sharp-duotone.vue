<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vfs6zn0ye"/><path class="xq01y1bfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:inbox-arrow-down-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vfs6zn0ye {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 13L21 12.4356L17.75 7.1361L19.455 6.0905L22.8525 11.6306C22.9489 11.7879 23 11.9689 23 12.1534L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 12.1534C1 11.9689 1.0511 11.7879 1.1475 11.6306L4.545 6.0905L6.25 7.1361L3 12.4356L3 13L8 13L10 16L14 16L16 13Z");
  stroke: none;
}

.xq01y1bfb {
  d: path("M1 13L8 13L10 16L14 16L16 13L23 13M12 3L12 11M8.7071 7.7071L12 11L15.2929 7.7071");
}

</style>
