<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4zkhxbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-full-sharp" /></template>
<style>
.t4zkhxbic {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6L18 6L18 18L2 18L2 6ZM22 8.5L22 15.5M6 9L6 15M10 9L10 15M14 9L14 15");
}

</style>
