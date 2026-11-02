<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxl4fcb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-round" /></template>
<style>
.fxl4fcb4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15c-4.622-1.734-2.894-8.645 2-8a4 4 0 1 1 8 0c4.894-.645 6.622 6.266 2 8v2a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4zm0 2h12");
}

</style>
