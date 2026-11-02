<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqg4ixbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backspace-round" /></template>
<style>
.kqg4ixbfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 6h2a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4h-7c-.64 0-1.36-.36-2-1l-4-4a1.414 1.414 0 0 1 0-2l4-4c.64-.64 1.36-1 2-1zm-2 4l4 4m0-4l-4 4");
}

</style>
