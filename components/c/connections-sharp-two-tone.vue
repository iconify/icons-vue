<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="iy80kzb9e"/><path class="qiufg0bav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:connections-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.iy80kzb9e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 17.5C11 19.9853 8.9853 22 6.5 22C4.0147 22 2 19.9853 2 17.5C2 15.0147 4.0147 13 6.5 13C8.9853 13 11 15.0147 11 17.5ZM22 6.5C22 8.9853 19.9853 11 17.5 11C15.0147 11 13 8.9853 13 6.5C13 4.0147 15.0147 2 17.5 2C19.9853 2 22 4.0147 22 6.5ZM10 5.5C10 7.9853 7.9853 10 5.5 10C3.0147 10 1 7.9853 1 5.5C1 3.0147 3.0147 1 5.5 1C7.9853 1 10 3.0147 10 5.5ZM23 18.5C23 20.9853 20.9853 23 18.5 23C16.0147 23 14 20.9853 14 18.5C14 16.0147 16.0147 14 18.5 14C20.9853 14 23 16.0147 23 18.5Z");
  stroke: none;
}

.qiufg0bav {
  d: path("M10 17.5C10 19.433 8.433 21 6.5 21C4.567 21 3 19.433 3 17.5C3 15.567 4.567 14 6.5 14C8.433 14 10 15.567 10 17.5ZM21 6.5C21 8.433 19.433 10 17.5 10C15.567 10 14 8.433 14 6.5C14 4.567 15.567 3 17.5 3C19.433 3 21 4.567 21 6.5ZM9 5.5C9 7.433 7.433 9 5.5 9C3.567 9 2 7.433 2 5.5C2 3.567 3.567 2 5.5 2C7.433 2 9 3.567 9 5.5ZM22 18.5C22 20.433 20.433 22 18.5 22C16.567 22 15 20.433 15 18.5C15 16.567 16.567 15 18.5 15C20.433 15 22 16.567 22 18.5ZM8.9749 15.0251L15.0251 8.9749");
}

</style>
