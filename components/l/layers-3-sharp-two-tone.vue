<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yujohsb3s"/><path class="ijg07k4ok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-3-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ijg07k4ok {
  d: path("M6.091 9.75L2 12L6.091 14.25M6.091 9.75L2 7.5L12 2L22 7.5L17.909 9.75M6.091 9.75L12 13L17.909 9.75M6.091 14.25L2 16.5L12 22L22 16.5L17.909 14.25M6.091 14.25L12 17.5L17.909 14.25M17.909 9.75L22 12L17.909 14.25");
}

.yujohsb3s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.634 1.069C11.908 0.961 12.219 0.98 12.481 1.124L22.481 6.624C22.801 6.8 23 7.135 23 7.5C23 7.865 22.801 8.2 22.481 8.376L19.983 9.749L22.482 11.124C22.802 11.3 23 11.636 23 12C23 12.364 22.802 12.7 22.482 12.876L19.983 14.25L22.481 15.624C22.801 15.8 23 16.135 23 16.5C23 16.865 22.801 17.2 22.481 17.376L12.481 22.876C12.182 23.041 11.818 23.041 11.519 22.876L1.519 17.376C1.199 17.2 1 16.865 1 16.5C1 16.135 1.199 15.8 1.519 15.624L4.017 14.25L1.519 12.876C1.199 12.7 1 12.365 1 12C1 11.635 1.199 11.3 1.519 11.124L4.017 9.75L1.519 8.376C1.199 8.2 1 7.865 1 7.5C1 7.135 1.199 6.8 1.519 6.624L11.519 1.124L11.634 1.069Z");
  stroke: none;
}

</style>
