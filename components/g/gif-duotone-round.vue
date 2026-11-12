<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdz6hnazb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gif-duotone-round" /></template>
<style>
.mdz6hnazb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8H5c-1 0-2 1-2 2v4c0 1 1 2 2 2h3v-4H6m6-4v8m9-8h-5v8m0-4h4");
}

</style>
