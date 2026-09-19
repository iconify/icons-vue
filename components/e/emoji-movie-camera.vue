<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pdg09db6j"/><path class="qlw08u2bd"/><path class="shl6vcb_v"/><path class="vqzrpdbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-movie-camera" /></template>
<style>
.pdg09db6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.492 31.817v4.879c0 .682.57 1.235 1.274 1.235H33.72V26.41H15.492v2.769");
}

.qlw08u2bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.286 25.972L5.5 31.144l3.426-.531l9.283 1.702q-.02.28.02.568a2.804 2.804 0 1 0 1.59-2.914L9.395 28.057zm27.434 8.515l8.78 2.271v-9.44l-8.78 2.088m-8.15-12.504a6.83 6.83 0 1 0 13.658.008v-.008a6.83 6.83 0 1 0-13.658-.005z");
}

.shl6vcb_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.35 16.902a2.049 2.049 0 1 0 4.098.002v-.002a2.049 2.049 0 1 0-4.097-.003zm-21.098 0a6.83 6.83 0 1 0 13.658.004v-.004a6.83 6.83 0 1 0-13.658 0");
}

.vqzrpdbia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.032 16.902a2.049 2.049 0 1 0 4.098 0v0a2.049 2.049 0 1 0-4.098 0");
}

</style>
