<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgniexb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4" /></template>
<style>
.lgniexb2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 20h18M5 20V6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v14m0-11h2a2 2 0 0 1 2 2v9M9 8h2m-2 4h2");
}

</style>
