<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0wfk2buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:life-buoy-sharp" /></template>
<style>
.h0wfk2buu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6a8.485 8.485 0 1 1 12 12A8.485 8.485 0 0 1 6 6m3 3a4.243 4.243 0 1 1 6 6a4.243 4.243 0 0 1-6-6M6 6l3 3m9-3l-3 3m3 9l-3-3m-9 3l3-3");
}

</style>
