<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmj8_vb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artefact-measure" /></template>
<style>
.jmj8_vb2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5.5L12 4l6.5 3l-1.5 5.5l-5.5-1.5l-5 2ZM3 19h18M3 16v3m18-3v3m-9-2.5V19");
}

</style>
