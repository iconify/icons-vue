<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgt-gxc7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cog-railway-round" /></template>
<style>
.dgt-gxc7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 19V9a2 2 0 0 1 2-2h3V6a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2v7zm0-7h5V9h7m-7-2v2M4 20l16-8M6 19l1 2m3-4l1 2m3-4l1 2m3-4l1 2");
}

</style>
