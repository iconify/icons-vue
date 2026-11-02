<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdeklzbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hourglass-round" /></template>
<style>
.vdeklzbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3v2c0 1.28.36 2.36 1 3l4 4l-4 4c-.64.64-1 1.72-1 3v2M17 3v2c0 1.28-.36 2.36-1 3l-4 4l4 4c.64.64 1 1.72 1 3v2M5 3h14M5 21h14");
}

</style>
