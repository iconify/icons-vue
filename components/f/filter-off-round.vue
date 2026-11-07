<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw75nfywc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:filter-off-round" /></template>
<style>
.iw75nfywc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h7a1 1 0 0 1 1 1c0 .64-.36 1.36-1 2l-2 2m-2.822 3.178c-.117.28-.178.558-.178.822v4c0 .613-.774 1.387-2 2c-.919.46-2-.081-2-1v-5c0-.64-.36-1.36-1-2L5 7c-.64-.64-1-1.36-1-2a1 1 0 0 1 1-1h1M4 2l14 14");
}

</style>
