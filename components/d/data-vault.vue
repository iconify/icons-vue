<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e9f9njbql"/><path class="tstmadcha"/><path class="rfu_0jh2w"/><path class="b303k4lpm"/><path class="zu7exta_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-vault" /></template>
<style>
.b303k4lpm {
  fill: currentColor;
  d: path("M11.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.e9f9njbql {
  d: path("M4.5 12a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0Z");
}

.rfu_0jh2w {
  d: path("M8.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.tstmadcha {
  fill: currentColor;
  d: path("M2.5 6.5H5v3H2.5Zm0 8H5v3H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zu7exta_u {
  d: path("m10.75 9.75l4.5 4.5m0-4.5l-4.5 4.5");
}

</style>
