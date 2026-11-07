<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo30m-cri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-close-round" /></template>
<style>
.zo30m-cri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 13v2a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h4M4 7l3 3c.64.64 1.72 1 3 1h3m3-7l4 4m0-4l-4 4");
}

</style>
