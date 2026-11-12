<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vssjn9bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heat-pump" /></template>
<style>
.vssjn9bcl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm4 14v2m10-2v2M7 11a5 5 0 0 1 10 0m0 0a5 5 0 0 1-10 0m5 0c-2 0-2-5 0-5m0 5c0-2 5-2 5 0m-5 0c2 0 2 5 0 5m0-5c0 2-5 2-5 0");
}

</style>
