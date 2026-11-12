<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxb22ec-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-corner-sharp" /></template>
<style>
.nxb22ec-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21H3V3h18v8M3 17l6-6l2 2m3-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

</style>
