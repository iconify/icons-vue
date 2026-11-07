<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f60qc-jxu"/><path class="t4l44ibvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-duotone-round" /></template>
<style>
.f60qc-jxu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 13v4c-.002.849-1.327 1.663-2 2c-.919.459-2-.081-2-1v-5c0-.773-.473-1.472-1-2L5 7c-.527-.528-1-1.227-1-2a1 1 0 0 1 1-1h1l8.178 8.178c-.108.26-.178.539-.178.822m-2-9h7a1 1 0 0 1 1 1c0 .773-.473 1.472-1 2l-2 2Z");
}

.ft5dv1b6b {
  fill: none;
}

.t4l44ibvm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h7a1 1 0 0 1 1 1c0 .64-.36 1.36-1 2l-2 2m-2.822 3.178c-.117.28-.178.558-.178.822v4c0 .613-.774 1.387-2 2c-.919.46-2-.081-2-1v-5c0-.64-.36-1.36-1-2L5 7c-.64-.64-1-1.36-1-2a1 1 0 0 1 1-1h1M4 2l14 14");
}

</style>
