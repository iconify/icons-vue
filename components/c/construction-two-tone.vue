<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rzxra0m-i"/><path class="p_8gpxwen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:construction-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p_8gpxwen {
  d: path("M4 4L20 4C21.1046 4 22 4.8954 22 6L22 9C22 10.1046 21.1046 11 20 11L4 11C2.8954 11 2 10.1046 2 9L2 6C2 4.8954 2.8954 4 4 4ZM5.5 11L12.5 4M11.5 11L18.5 4M6 11L6 20M18 11L18 20M4 20L8 20M16 20L20 20");
}

.rzxra0m-i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C21.6569 3 23 4.3431 23 6L23 9C23 10.6569 21.6569 12 20 12L4 12C2.3431 12 1 10.6569 1 9L1 6C1 4.3431 2.3431 3 4 3Z");
  stroke: none;
}

</style>
