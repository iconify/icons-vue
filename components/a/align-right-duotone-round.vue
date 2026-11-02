<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ymuo3i5hu"/><path class="kpc9-2j-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-right-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kpc9-2j-e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 7a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6H7a3 3 0 0 1-3-3m4 10a3 3 0 0 1 3-3h2a3 3 0 0 1 0 6h-2a3 3 0 0 1-3-3M20 3v18");
}

.ymuo3i5hu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 4h6a3 3 0 1 1 0 6H7a3 3 0 1 1 0-6m4 10h2a3 3 0 1 1 0 6h-2a3 3 0 1 1 0-6");
}

</style>
