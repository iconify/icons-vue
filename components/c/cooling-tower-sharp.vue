<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc7qvvbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooling-tower-sharp" /></template>
<style>
.mc7qvvbtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10h8m-8 0c.67 1 1 2.5 1 4c0 3-2 5.5-4 7m11-11c-.67 1-1 2.5-1 4c0 3 2 5.5 4 7M3 21h18M7 6a2 2 0 1 1 4 0a3 3 0 0 1 6 0");
}

</style>
