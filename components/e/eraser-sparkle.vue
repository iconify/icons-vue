<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swlef1k_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle" /></template>
<style>
.swlef1k_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 16l5-5a1.414 1.414 0 0 0 0-2l-3-3a1.414 1.414 0 0 0-2 0l-5 5m0 0l-5 5a1.414 1.414 0 0 0 0 2l2 2h4l4-4m-4 4h10m-11-9l5 5M6 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
