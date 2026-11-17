<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2bcer66e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-leaf-corner-fill-round" /></template>
<style>
.c2bcer66e {
  fill: currentColor;
  d: path("M17.714 9H12a3 3 0 0 0-3 3v9a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l3.08 2.695A1.001 1.001 0 0 1 17.714 9m-3.517 12.218l-.49.489a.999.999 0 1 1-1.414-1.414l.489-.49c-.75-1.72-.639-3.595.678-4.99c.736-.778 1.715-1.265 2.738-1.544c1.264-.343 2.594-.383 3.893-.265c.48.044.86.424.905.904v.001c.118 1.299.078 2.629-.265 3.893c-.279 1.023-.766 2.002-1.544 2.738c-1.395 1.317-3.27 1.428-4.99.678m1.096-3.925a.999.999 0 1 1 1.414 1.414l-.926.926c1.658.317 2.614-.868 3.02-2.356c.205-.757.269-1.548.252-2.33c-.782-.017-1.573.047-2.33.252c-1.488.406-2.673 1.362-2.356 3.02Z");
}

</style>
