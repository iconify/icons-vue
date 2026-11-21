<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dahhbepwr"/><path class="tmgr3kbcl"/><path class="f_ktfu2lg"/><path class="isy2lrdil"/><path class="dvm6z8bvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-scan-sharp-duotone" /></template>
<style>
.dahhbepwr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 12L14 21C14 21.5523 13.5523 22 13 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2L13 2C13.5523 2 14 2.4477 14 3Z");
  stroke: none;
}

.dvm6z8bvq {
  stroke-opacity: 0.4;
  d: path("M17 2L17 3L17 10L17 11M17 22L17 21L17 14L17 13M21 21L21 20L21 18L21 17M21 15L21 14L21 10L21 9M21 7L21 6L21 4L21 3");
}

.f_ktfu2lg {
  d: path("M13 23L13 22L13 21L13 15.5128L13 3L13 2L13 1");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.isy2lrdil {
  fill: currentColor;
  d: path("M9.5 7.5C9.5 8.3284 8.8284 9 8 9C7.1716 9 6.5 8.3284 6.5 7.5C6.5 6.6716 7.1716 6 8 6C8.8284 6 9.5 6.6716 9.5 7.5Z");
  stroke: none;
}

.tmgr3kbcl {
  fill: currentColor;
  d: path("M2 17.5858L2.2929 17.2929L8.2929 11.2929C8.6834 10.9024 9.3166 10.9024 9.7071 11.2929L12.7872 14.373C12.8305 14.4163 12.8788 14.4493 12.9299 14.473C12.9815 14.4969 13.037 14.5119 13.0938 14.5172L14 14.6026L14 16.6115L12.9062 16.5084C12.6256 16.4819 12.3488 16.4081 12.0885 16.2874C11.8279 16.1665 11.5849 15.9991 11.373 15.7872L9 13.4142L3.7071 18.7071L2 20.4142Z");
  stroke: none;
}

</style>
