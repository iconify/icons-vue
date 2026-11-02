<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5jge9bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-alt-duocolor" /></template>
<style>
.k5jge9bek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 7l1-1a4.243 4.243 0 0 1 6 6l-6 6a1.414 1.414 0 0 1-2 0l-6-6a4.243 4.243 0 0 1 6-6z");
}

</style>
