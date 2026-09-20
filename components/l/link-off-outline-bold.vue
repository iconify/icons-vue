<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e-g8-f9ol"/><path class="rf-csebev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:link-off-outline-bold" /></template>
<style>
.e-g8-f9ol {
  d: path("M2 8a3 3 0 0 1 3 -3h3a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

.rf-csebev {
  d: path("M13 16a3 3 0 0 1 3 -3h3a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-3a3 3 0 0 1 -3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
