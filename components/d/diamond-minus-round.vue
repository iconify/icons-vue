<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsouho3oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-minus-round" /></template>
<style>
.xsouho3oe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 18l-2 2a4.243 4.243 0 0 1-6 0l-5-5a4.243 4.243 0 0 1 0-6l5-5a4.243 4.243 0 0 1 6 0l5 5a4.243 4.243 0 0 1 0 6zm-8-6h6");
}

</style>
