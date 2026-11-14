<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owu0vk44o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-scissors" /></template>
<style>
.owu0vk44o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 18.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm10 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-5.25-2.5l9-13.75m-2.5 13.75l-9-13.75");
}

</style>
