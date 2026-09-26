<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="cnm4tobcu"/><path class="d0kgfogdx"/><path class="hxiqqwbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-off-sharp-two-tone" /></template>
<style>
.cnm4tobcu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.25 5.25L18.75 18.75C16.8543 20.1721 14.5069 21 12 21C6.7383 21 2.1794 17.3529 1.0244 12.2195C0.9919 12.075 0.9919 11.925 1.0244 11.7805C1.6291 9.0929 3.1668 6.8127 5.25 5.25Z");
  stroke: none;
}

.d0kgfogdx {
  stroke-opacity: 0.4;
  d: path("M8.8995 4.4277L9.88 4.2211C10.565 4.076 11.2752 4 12 4C16.794 4 20.9477 7.3229 22 12C21.7487 13.1169 21.3206 14.1566 20.7491 15.0922L20.0706 16.2029");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hxiqqwbdc {
  d: path("M18.035 18.035C16.3283 19.2786 14.2337 20 12 20C7.206 20 3.0523 16.6771 2 12C2.562 9.5021 4.0086 7.3904 5.965 5.965M14.1213 14.1213C13.5785 14.6642 12.8285 15 12 15C10.3431 15 9 13.6569 9 12C9 11.1716 9.3358 10.42 9.88 9.88M1.7071 1.7071L22.2929 22.2929");
}

</style>
