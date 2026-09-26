<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rjqp7ubcm"/><path class="a3uio9zoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:droplet-off-sharp-two-tone" /></template>
<style>
.a3uio9zoc {
  stroke-linejoin: miter;
  stroke-opacity: 0.4;
  d: path("M10.6576 5.0008L12 3.5L17.2175 9.3333C18.207 10.4396 18.8193 11.8319 18.9658 13.309");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjqp7ubcm {
  d: path("M17.8477 17.8477C16.553 19.8154 14.3555 21 12 21C8.134 21 5 17.866 5 14C5 12.2782 5.6346 10.6167 6.7825 9.3333L7.9868 7.9868M1.7071 1.7071L22.2929 22.2929");
}

</style>
