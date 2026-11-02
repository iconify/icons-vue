<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-45c4bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:command-duocolor-sharp" /></template>
<style>
.g-45c4bfm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9V6a3 3 0 1 0-3 3zm6 0V6a3 3 0 1 1 3 3zm0 6v3a3 3 0 1 0 3-3zm-6 0v3a3 3 0 1 1-3-3zm0-6h6v6H9Z");
}

</style>
