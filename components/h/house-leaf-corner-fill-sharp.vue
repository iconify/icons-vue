<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuq91k3hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-leaf-corner-fill-sharp" /></template>
<style>
.kuq91k3hp {
  fill: currentColor;
  d: path("m12.659 2.247l5.714 5A1.001 1.001 0 0 1 17.714 9H9v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V10c0-.288.124-.563.341-.753l8-7c.378-.329.94-.329 1.318 0m1.538 18.971l-.49.489a.999.999 0 1 1-1.414-1.414l.489-.49c-.75-1.72-.639-3.595.678-4.99c.736-.778 1.715-1.265 2.738-1.544c1.264-.343 2.594-.383 3.893-.265c.48.044.86.424.905.904v.001c.118 1.299.078 2.629-.265 3.893c-.279 1.023-.766 2.002-1.544 2.738c-1.395 1.317-3.27 1.428-4.99.678m1.096-3.925a.999.999 0 1 1 1.414 1.414l-.926.926c1.658.317 2.614-.868 3.02-2.356c.205-.757.269-1.548.252-2.33c-.782-.017-1.573.047-2.33.252c-1.488.406-2.673 1.362-2.356 3.02Z");
}

</style>
