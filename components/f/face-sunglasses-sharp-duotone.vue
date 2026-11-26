<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ijid82e0h"/><path clip-rule="evenodd" class="ue6pubc6w"/><path class="nkbqrzihs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-sunglasses-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ijid82e0h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12.0083C22.9955 18.0796 18.0723 23 12 23C8.9627 23 6.2114 21.7677 4.2218 19.7782C2.2323 17.7886 1 15.0373 1 12L1 7C1 6.4477 1.4477 6 2 6L2.7804 6C4.8021 2.8924 8.2663 1 12 1C13.9649 1 15.8555 1.5242 17.5 2.4737C18.9803 3.3284 20.2619 4.5279 21.2197 6.0001L22 6.0001C22.5523 6.0001 23 6.4478 23 7.0001Z");
  stroke: none;
}

.nkbqrzihs {
  d: path("M8.7071 15.7071L9 16C10 17 11 17.5 12 17.5C13 17.5 14 17 15 16L15.2929 15.7071");
}

.ue6pubc6w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 9L11 12C11 12.5523 10.5523 13 10 13L2 13C1.4477 13 1 12.5523 1 12L1 7C1 6.4477 1.4477 6 2 6L6 6L10 6C10.5523 6 11 6.4477 11 7L13 7C13 6.4477 13.4477 6 14 6L18 6L22 6C22.5523 6 23 6.4477 23 7L23 12C23 12.5523 22.5523 13 22 13L14 13C13.4477 13 13 12.5523 13 12L13 9Z");
  stroke: none;
}

</style>
