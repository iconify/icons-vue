<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe7xj8bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:globe-dots" /></template>
<style>
.fe7xj8bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 0 0-14 0m7-7c-1.657 0-3 3.134-3 7s1.343 7 3 7s3-3.134 3-7s-1.343-7-3-7m-7 7h14M4 4h.01M20 4h.01M4 20h.01M20 20h.01");
}

</style>
