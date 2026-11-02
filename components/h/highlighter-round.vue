<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfy499bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-round" /></template>
<style>
.vfy499bjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m7 11l4-4a4.243 4.243 0 0 1 6 6l-4 4zm1 1l-4 4c-.64.64-1 1.36-1 2v1a1 1 0 0 0 1 1h3c.64 0 1.36-.36 2-1l3-3");
}

</style>
