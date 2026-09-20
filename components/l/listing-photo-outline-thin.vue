<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d5czi6rdr"/><path class="g7cpaab_q"/><path class="rqhdq8b3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:listing-photo-outline-thin" /></template>
<style>
.d5czi6rdr {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.g7cpaab_q {
  d: path("m6 9 3 -3 3 3 2 -2 2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rqhdq8b3d {
  d: path("M7 14.5a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2V17a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

</style>
