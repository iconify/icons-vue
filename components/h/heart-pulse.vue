<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpi0bvd3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-pulse" /></template>
<style>
.dpi0bvd3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7c-2-4-9-4-9 2s9 11 9 11s9-5 9-11s-7-6-9-2m-8 5h3l1-3l2 6l1-3h9");
}

</style>
