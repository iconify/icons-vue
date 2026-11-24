<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ktj4b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-search-sharp" /></template>
<style>
.w1ktj4b8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9h16v12H4Zm4 0V7a4 4 0 1 1 8 0v2m-7 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

</style>
