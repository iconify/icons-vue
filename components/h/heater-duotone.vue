<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qfmwl0bde"/><path class="gfli8dbac"/><path clip-rule="evenodd" class="zoga1lc_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heater-duotone" /></template>
<style>
.gfli8dbac {
  d: path("M18 10L18 16M14 10L14 16M10 10L10 16M9 6C9 5.2131 9.3705 4.4721 10 4C10.6295 3.5279 11 2.7869 11 2M14 6C14 5.2131 14.3705 4.4721 15 4C15.6295 3.5279 16 2.7869 16 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qfmwl0bde {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 21L6 21L6 22C6 22.5523 5.5523 23 5 23C4.4477 23 4 22.5523 4 22L4 21C2.3431 21 1 19.6569 1 18L1 7C1 5.3431 2.3431 4 4 4L20 4C21.6569 4 23 5.3431 23 7L23 18C23 19.6569 21.6569 21 20 21L20 22C20 22.5523 19.5523 23 19 23C18.4477 23 18 22.5523 18 22L18 21Z");
  stroke: none;
}

.zoga1lc_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 10C7 10.5523 6.5523 11 6 11C5.4477 11 5 10.5523 5 10C5 9.4477 5.4477 9 6 9C6.5523 9 7 9.4477 7 10ZM7 14C7 14.5523 6.5523 15 6 15C5.4477 15 5 14.5523 5 14C5 13.4477 5.4477 13 6 13C6.5523 13 7 13.4477 7 14Z");
  stroke: none;
}

</style>
