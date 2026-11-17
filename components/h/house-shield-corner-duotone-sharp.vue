<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="msdxzxwfr"/><path class="np3xx7blg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-shield-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.msdxzxwfr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.714 8H8v13H4V10l8-7ZM13 13h8v3c-.002 2.649-1.701 4.08-4 5c-2.299-.92-3.998-2.351-4-5Z");
}

.np3xx7blg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 21H4V10l8-7l5.714 5M17 13h4v3c0 2.5-1.5 4-4 5c-2.5-1-4-2.5-4-5v-3z");
}

</style>
