<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbcov6btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:haptic-glove" /></template>
<style>
.bbcov6btt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.5v-4L3.25 14c-.75-.75.25-2.25 1.25-1.5l.5.25V8a1.5 1.5 0 0 1 3 0V5.5a1.5 1.5 0 0 1 3 0v1a1.5 1.5 0 0 1 3 0V16c0 .75-.5 1.25-.5 2v3.5M8 8v4m3-5.5V12m4.505-8.505a4.25 4.25 0 0 1 0 6.01m2.524-6.877a6.75 6.75 0 0 1 0 7.744m2.854-7.781a9.25 9.25 0 0 1 0 7.818");
}

</style>
