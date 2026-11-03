<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="kbgwl6b_c"/><path class="qkdrdtb4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kbgwl6b_c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M14.2154 14.2154C13.6083 14.3641 13.0221 14.5882 12.4706 14.8824C11.0947 15.6162 9.5593 16 8 16C6.4407 16 4.9053 15.6162 3.5294 14.8824C3.2035 14.7086 3 14.3693 3 14L3 3L14.2154 14.2154ZM6.6134 2.8707C7.0706 2.9567 7.5348 3 8 3C9.2311 3 10.4432 2.697 11.5294 2.1176C12.9053 1.3838 14.4407 1 16 1C17.5593 1 19.0947 1.3838 20.4706 2.1176C20.7965 2.2914 21 2.6307 21 3L21 14C21.0001 14.5523 20.5524 15.0001 20.0001 15.0001C19.8359 15.0001 19.6743 14.9597 19.5294 14.8824C19.0496 14.6265 18.5434 14.4235 18.0197 14.2771L6.6134 2.8707Z");
  stroke: none;
}

.qkdrdtb4i {
  d: path("M4 14C5.2311 14.6566 6.6048 15 8 15C9.3952 15 10.7689 14.6566 12 14C12.4514 13.7593 12.9219 13.5606 13.4056 13.4056M4 4L4 23M1.7071 1.7071L22.2929 22.2929");
}

</style>
