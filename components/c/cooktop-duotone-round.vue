<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xa7inn8kq"/><path class="qs9d65muj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooktop-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qs9d65muj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm3 1a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0m8 0a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0m-8 8a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0m8 0a2 2 0 1 1 4 0m0 0a2 2 0 1 1-4 0");
}

.xa7inn8kq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h10a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4");
}

</style>
