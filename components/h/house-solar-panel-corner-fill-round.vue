<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pykukivlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-solar-panel-corner-fill-round" /></template>
<style>
.pykukivlp {
  fill: currentColor;
  d: path("M17.714 9H12a3 3 0 0 0-3 3v9a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l3.08 2.695A1.001 1.001 0 0 1 17.714 9M21 22h-8a1 1 0 0 1-.992-1.124l1-8A1 1 0 0 1 14 12h6a1 1 0 0 1 .992.876l1 8A.997.997 0 0 1 21 22m-6.117-8l-.25 2H16v-2ZM18 16h1.367l-.25-2H18Zm-3.617 2l-.25 2H16v-2Zm5.234 0H18v2h1.867Z");
}

</style>
