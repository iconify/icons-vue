<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fnobgdc3o"/><path class="f4kk70brf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-single-sharp-two-tone" /></template>
<style>
.f4kk70brf {
  d: path("M4 11L20 11L20 20L4 20L4 11ZM7 11L7 4L17 4L17 11M4 15L20 15");
}

.fnobgdc3o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 20L3 11C3 10.4477 3.4477 10 4 10L6 10L6 4C6 3.4477 6.4477 3 7 3L17 3C17.5523 3 18 3.4477 18 4L18 10L20 10C20.5523 10 21 10.4477 21 11L21 20C21 20.5523 20.5523 21 20 21L4 21C3.4477 21 3 20.5523 3 20Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
