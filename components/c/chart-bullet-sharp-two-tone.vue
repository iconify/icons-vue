<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hljch-bye"/><path class="p53xcyb3q"/><path class="cpby9zlid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bullet-sharp-two-tone" /></template>
<style>
.cpby9zlid {
  d: path("M7 10L21 10L21 14L7 14ZM16 6L16 18");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hljch-bye {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 9L21 9C21.5523 9 22 9.4477 22 10L22 14C22 14.5523 21.5523 15 21 15L7 15C6.4477 15 6 14.5523 6 14L6 10C6 9.4477 6.4477 9 7 9Z");
  stroke: none;
}

.p53xcyb3q {
  stroke-opacity: 0.4;
  d: path("M3 2L3 21L22 21");
}

</style>
