<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x024csb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-help" /></template>
<style>
.x024csb8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 17l-4 4a1.414 1.414 0 0 1-2 0l-8-8a1.414 1.414 0 0 1 0-2l8-8a1.414 1.414 0 0 1 2 0l8 8a1.414 1.414 0 0 1 0 2zm-7-6a2 2 0 1 1 2 2m0 3h.01");
}

</style>
