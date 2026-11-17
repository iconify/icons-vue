<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lzypupf2v"/><path class="gvm3ojbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-pin-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gvm3ojbxx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21H4V10l8-7l5.714 5M15 13h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

.lzypupf2v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.714 8H8v13H4V10l8-7ZM15 13h4v3l2 2h-8l2-2Z");
}

</style>
