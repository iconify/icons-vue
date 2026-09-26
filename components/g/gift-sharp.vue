<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2496vbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gift-sharp" /></template>
<style>
.m2496vbfl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 7L2 7L2 11L22 11L22 7ZM12 7C9 7 7 6 7 4.5C7 3.1193 8.1193 2 9.5 2C11.5 2 12 5 12 7ZM12 7C15 7 17 6 17 4.5C17 3.1193 15.8807 2 14.5 2C12.5 2 12 5 12 7ZM4 11L4 22L20 22L20 11L4 11Z");
}

</style>
