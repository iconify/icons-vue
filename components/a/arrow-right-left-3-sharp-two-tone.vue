<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kb__roanq"/><path class="h4h_itruf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-left-3-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h4h_itruf {
  d: path("M14 17L13 17L2.7396 17L2.0856 17M7.1888 11.6995L6.8947 12L2 17L6.8947 22L7.1888 22.3005");
}

.kb__roanq {
  stroke-opacity: 0.4;
  d: path("M10 7L11 7L21.2604 7L21.9144 7M16.8112 12.3005L17.1053 12L22 7L17.1053 2L16.8112 1.6995");
}

</style>
