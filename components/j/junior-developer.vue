<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idrd42bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:junior-developer" /></template>
<style>
.idrd42bbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM2.5 21c0-4 3.5-6.5 7.5-6.5c.584 0 1.158.053 1.711.157M18 21.5v-5m0 1c0-2.5 1.5-3.5 3.5-3.5c0 2.5-1.5 3.5-3.5 3.5Zm0 1c0-2-1.5-3-3.5-3c0 2 1.5 3 3.5 3Z");
}

</style>
