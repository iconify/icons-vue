<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x2l2t0bcl"/><path class="b8wntzbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-x-sharp-two-tone" /></template>
<style>
.b8wntzbce {
  d: path("M3 14L10 14L10 21L3 21L3 14ZM3 3L10 3L10 10L3 10L3 3ZM14 3L21 3L21 10L14 10L14 3ZM14.7071 14.7071L20.2929 20.2929M20.2929 14.7071L14.7071 20.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x2l2t0bcl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 13L10 13C10.5523 13 11 13.4477 11 14L11 21C11 21.5523 10.5523 22 10 22L3 22C2.4477 22 2 21.5523 2 21L2 14C2 13.4477 2.4477 13 3 13ZM3 2L10 2C10.5523 2 11 2.4477 11 3L11 10C11 10.5523 10.5523 11 10 11L3 11C2.4477 11 2 10.5523 2 10L2 3C2 2.4477 2.4477 2 3 2ZM14 2L21 2C21.5523 2 22 2.4477 22 3L22 10C22 10.5523 21.5523 11 21 11L14 11C13.4477 11 13 10.5523 13 10L13 3C13 2.4477 13.4477 2 14 2Z");
  stroke: none;
}

</style>
