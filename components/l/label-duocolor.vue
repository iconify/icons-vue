<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_jcocqtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:label-duocolor" /></template>
<style>
.g_jcocqtl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6h4c.64 0 1.36.36 2 1l4 4a1.414 1.414 0 0 1 0 2l-4 4c-.64.64-1.36 1-2 1H6a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2z");
}

</style>
