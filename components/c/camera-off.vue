<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pztyh98zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:camera-off" /></template>
<style>
.pztyh98zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.54 4.54c.488-.35.995-.54 1.46-.54h2c.64 0 1.36.36 2 1l2 2h2a2 2 0 0 1 2 2v7m-2 4H5a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h1m3.879 3.879a3 3 0 0 0 4.243 4.243M2 3l19 19");
}

</style>
