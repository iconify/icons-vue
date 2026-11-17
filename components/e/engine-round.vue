<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceo5crbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:engine-round" /></template>
<style>
.ceo5crbep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14v3a1 1 0 0 1-1 1h-1a1 1 0 0 1-1-1a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1v2a1 1 0 0 1-1 1h-3l-2-4H7a1 1 0 0 1-1-1v-4l3-3h4l2 4h2a1 1 0 0 0 1-1a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1zM9 4h4m-2 0v4m-8 3v4m0-2h3");
}

</style>
