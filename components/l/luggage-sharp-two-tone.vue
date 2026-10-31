<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nsn6mqbuc"/><path class="zrojaywrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:luggage-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nsn6mqbuc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5L19 5C19.5523 5 20 5.4477 20 6L20 20C20 20.5523 19.5523 21 19 21L5 21C4.4477 21 4 20.5523 4 20L4 6C4 5.4477 4.4477 5 5 5Z");
  stroke: none;
}

.zrojaywrh {
  d: path("M5 6L19 6L19 20L5 20ZM5 11L19 11M7 20L7 23M17 20L17 23M8 6L9 2L15 2L16 6");
}

</style>
