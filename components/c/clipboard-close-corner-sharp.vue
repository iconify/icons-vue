<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stl1nib5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-close-corner-sharp" /></template>
<style>
.stl1nib5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 5H5v16h4M19 9V5h-4M9 5V3h6v2M9 5v2h6V5m-1 9l6 6m0-6l-6 6");
}

</style>
