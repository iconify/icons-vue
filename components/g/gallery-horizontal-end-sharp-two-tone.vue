<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jojzoaclr"/><path class="i380w0woj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-horizontal-end-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i380w0woj {
  d: path("M11 3L21 3L21 21L11 21L11 3ZM7 4L7 20M3 6L3 18");
}

.jojzoaclr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L11 22C10.4477 22 10 21.5523 10 21L10 3C10 2.4477 10.4477 2 11 2Z");
  stroke: none;
}

</style>
