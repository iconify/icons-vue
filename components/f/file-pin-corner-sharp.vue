<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp-1ygkak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pin-corner-sharp" /></template>
<style>
.dp-1ygkak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H5v18h4m4-18l6 6m-6-6v6h6m-4 4h4v3l2 2h-8l2-2zm-1 0h6m-3 5v3");
}

</style>
