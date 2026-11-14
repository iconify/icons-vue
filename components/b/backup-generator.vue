<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nxv4a1baw"/><path class="nta6tybyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backup-generator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nta6tybyw {
  d: path("M13 9.75L10 13h4l-3 3.25M5.5 19v2m13-2v2");
}

.nxv4a1baw {
  d: path("M6.5 7h11a3.5 3.5 0 0 1 3.5 3.5v5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 15.5v-5A3.5 3.5 0 0 1 6.5 7M5 7V4h14v3");
}

</style>
