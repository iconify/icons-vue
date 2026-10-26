<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o50bydw3s"/><path class="pr11-kbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-taxi-front-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o50bydw3s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.0011 5L18 5C18.5026 5 18.9271 5.373 18.9917 5.8714L19.6294 10.7904L19.6924 11L21 11C21.5523 11 22 11.4477 22 12L22 20C22 20.5523 21.5523 21 21 21L20 21L20 22C20 22.5523 19.5523 23 19 23L18 23C17.4477 23 17 22.5523 17 22L17 21L7 21L7 22C7 22.5523 6.5523 23 6 23L5 23C4.4477 23 4 22.5523 4 22L4 21L3 21C2.4477 21 2 20.5523 2 20L2 12C2 11.4477 2.4477 11 3 11L4.3076 11L4.3706 10.7904L5.0083 5.8714C5.0729 5.373 5.4974 5 6 5L7.9989 5L9.5936 1.5776C9.7578 1.2253 10.1113 1 10.5 1L13.5 1C13.8887 1 14.2422 1.2253 14.4064 1.5776L16.0011 5Z");
  stroke: none;
}

.pr11-kbtf {
  d: path("M3 12L21 12L21 20L3 20ZM5.0513 12L5.35177 11L6 6L18 6L18.6482 11L18.9487 12M8.63617 6L10.5 2L13.5 2L15.3638 6M18 20L19 20L19 22L18 22ZM5 20L6 20L6 22L5 22ZM5.35177 11L2.5 11M18.6482 11L21.5 11M6 16L9 16M15 16L18 16");
}

</style>
