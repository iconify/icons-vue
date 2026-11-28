<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r_s6bibvl"/><path class="qji-vnbbo"/><path clip-rule="evenodd" class="hj93jjxzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-kiss-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hj93jjxzb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.458 20.817C14.719 20.106 14 19.163 14 17.917C14 17.08 14.374 16.341 14.941 15.823C15.507 15.306 16.273 15 17.1 15C17.608 15 18.078 15.118 18.5 15.324C18.922 15.118 19.392 15 19.9 15C20.727 15 21.493 15.306 22.059 15.823C22.626 16.341 23 17.08 23 17.917C23 19.163 22.281 20.106 21.542 20.817C21.165 21.18 20.743 21.52 20.334 21.838C19.911 22.167 19.52 22.46 19.131 22.776C18.953 22.921 18.73 23 18.5 23C18.27 23 18.047 22.921 17.869 22.776C17.48 22.46 17.089 22.167 16.666 21.838C16.257 21.52 15.835 21.18 15.458 20.817ZM12 16.5C12 17.328 11.328 18 10.5 18C9.672 18 9 17.328 9 16.5C9 15.672 9.672 15 10.5 15C11.328 15 12 15.672 12 16.5Z");
  stroke: none;
}

.qji-vnbbo {
  d: path("M9 9V12M15 9V12");
}

.r_s6bibvl {
  stroke-opacity: 0.4;
  d: path("M12.524 21.986C12.349 21.996 12.175 22 12 22C6.477 22 2 17.523 2 12C2 6.477 6.477 2 12 2C17.523 2 22 6.477 22 12C22 12.175 21.996 12.349 21.986 12.524");
}

</style>
