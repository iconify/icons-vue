<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="roiy7wbhh"/><path class="x3zol5j3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layer-mask-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.roiy7wbhh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3L3 3ZM22 17.343L8.657 4L8.657 3L22 3C22.5523 3 23 3.4477 23 4L23 17.343Z");
  stroke: none;
}

.x3zol5j3a {
  d: path("M4 4L2 4L2 20L20 20M8.657 4L22 4L22 17.343M14.8284 14.8284C14.0783 15.5786 13.0609 16 12 16C9.7909 16 8 14.2091 8 12C8 10.9391 8.4214 9.9217 9.1716 9.1716M1.7071 1.7071L22.2929 22.2929");
}

</style>
