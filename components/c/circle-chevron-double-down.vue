<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfb3wtbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-double-down" /></template>
<style>
.nfb3wtbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m6 2l3 3l3-3M9 8l3 3l3-3");
}

</style>
