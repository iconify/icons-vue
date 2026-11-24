<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf6h_ccqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-sun" /></template>
<style>
.kf6h_ccqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H6a2 2 0 0 1-2-2v-8.092a2 2 0 0 1 .683-1.506l6-5.25a2 2 0 0 1 2.634 0l6 5.25A2 2 0 0 1 20 10.908V19a2 2 0 0 1-2 2zm-1-8a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5 0h.5m-1.672 2.828l.354.354M12 17v.5m-2.828-1.672l-.354.354M8 13h-.5m1.672-2.828l-.354-.354M12 9v-.5m2.828 1.672l.354-.354");
}

</style>
