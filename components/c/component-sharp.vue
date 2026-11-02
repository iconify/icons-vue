<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpyj28b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:component-sharp" /></template>
<style>
.bpyj28b6r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 4l2 2l-4 4l-4-4l4-4zm-6 6l2 2l-4 4l-4-4l4-4zm12 0l2 2l-4 4l-4-4l4-4zm-6 6l2 2l-4 4l-4-4l4-4z");
}

</style>
