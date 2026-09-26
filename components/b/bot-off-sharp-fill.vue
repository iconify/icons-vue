<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="wel3ij-ab"/><path class="ur0kqubed"/><path class="sp3ujwwyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sp3ujwwyq {
  fill: currentColor;
  d: path("M13.5 3.5C13.5 4.3284 12.8284 5 12 5C11.1716 5 10.5 4.3284 10.5 3.5C10.5 2.6716 11.1716 2 12 2C12.8284 2 13.5 2.6716 13.5 3.5Z");
  stroke: none;
}

.ur0kqubed {
  d: path("M1 14.5L4 14.5M12 8L12 3.5M20 14.5L23 14.5M1.7071 1.7071L22.2929 22.2929");
}

.wel3ij-ab {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 8C3 7.4477 3.4477 7 4 7L7 7L21 21ZM8 12.5858L8 14L10 14L10 12.5858L8 12.5858ZM9 16L9 18L13 18L13 16L9 16ZM9.5858 7L20 7C20.5523 7 21 7.4477 21 8L21 18.4142L9.5858 7Z");
  stroke: none;
}

</style>
