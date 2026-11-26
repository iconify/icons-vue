<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqjqkjsgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-inline" /></template>
<style>
.rqjqkjsgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 9L14 9C14.5523 9 15 9.4477 15 10L15 14C15 14.5523 14.5523 15 14 15L10 15C9.4477 15 9 14.5523 9 14L9 10C9 9.4477 9.4477 9 10 9ZM3 3H21M3 21H21M3 12H5M19 12H21");
}

</style>
