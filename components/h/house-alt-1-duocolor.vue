<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iip30ke_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-1-duocolor" /></template>
<style>
.iip30ke_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 17v2a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-7c0-.64-.36-1.36-1-2l-6-6a1.414 1.414 0 0 0-2 0l-6 6c-.64.64-1 1.36-1 2v7a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-2a2 2 0 1 1 4 0");
}

</style>
