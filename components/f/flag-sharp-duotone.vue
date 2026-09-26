<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ahv5xvbvk"/><path class="qbgtuxb9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-sharp-duotone" /></template>
<style>
.ahv5xvbvk {
  fill: currentColor;
  d: path("M3 14C3 14.3693 3.2035 14.7086 3.5294 14.8824C4.9053 15.6162 6.4407 16 8 16C9.5593 16 11.0947 15.6162 12.4706 14.8824C13.5568 14.303 14.7689 14 16 14C17.2311 14 18.4432 14.303 19.5294 14.8824C19.6742 14.9596 19.8359 15 20 15C20.5523 15 21 14.5523 21 14L21 3C21 2.6307 20.7965 2.2914 20.4706 2.1176C19.0947 1.3838 17.5593 1 16 1C14.4407 1 12.9053 1.3838 11.5294 2.1176C10.4432 2.697 9.2311 3 8 3C6.7689 3 5.5568 2.697 4.4706 2.1176C4.3258 2.0404 4.1641 2 4 2C3.4477 2 3 2.4477 3 3L3 14Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbgtuxb9a {
  stroke-opacity: 0.4;
  d: path("M4 2.398L4 3L4 23");
}

</style>
