<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4lj602_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clapperboard-sharp" /></template>
<style>
.e4lj602_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9h18v12H3Zm0-3l16-3l.563 3l-16 3zm5.333-1l.563 3m4.77-4l.563 3M10 12l5 3l-5 3z");
}

</style>
