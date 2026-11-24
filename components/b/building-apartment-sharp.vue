<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt10tjffw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-apartment-sharp" /></template>
<style>
.rt10tjffw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h18M7 21V4h10v17M10 8h.01M14 8h.01M10 12h.01M14 12h.01M10 21v-4h4v4M7 11H3v10m14-10h4v10");
}

</style>
