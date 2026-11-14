<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fpqzlxbok"/><path class="dps_k9bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discoloured-water" /></template>
<style>
.dps_k9bgq {
  fill: currentColor;
  d: path("M10 17a4.5 4.5 0 0 0 9 0Z");
}

.fpqzlxbok {
  d: path("M4 3h8a4 4 0 0 1 4 4v1.5h-3V7a1 1 0 0 0-1-1H4Zm10.5 8.5C16.5 14 19 16 19 17a4.5 4.5 0 0 1-9 0c0-1 2.5-3 4.5-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
