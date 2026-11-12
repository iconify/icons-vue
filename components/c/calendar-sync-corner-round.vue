<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvauedbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-sync-corner-round" /></template>
<style>
.hvauedbie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 21H8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4M8 3v2m8-2v2M4 9h16m1 10a4.472 4.472 0 0 1-8 0m3 0h-3v3m0-7a4.472 4.472 0 0 1 8 0m-3 0h3v-3");
}

</style>
