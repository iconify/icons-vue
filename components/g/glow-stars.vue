<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph39cd57v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glow-stars" /></template>
<style>
.ph39cd57v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 7l2.057 4.668l5.076.514l-3.804 3.4l1.079 4.986L12 18l-4.408 2.568l1.079-4.986l-3.804-3.4l5.076-.514Zm0-4.5v1.75M3.5 6.5l2 1.5m15-1.5l-2 1.5");
}

</style>
