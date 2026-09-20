<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zlnwgebrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-print-48-filled" /></template>
<style>
.zlnwgebrs {
  fill: currentColor;
  d: path("M18 26a3 3 0 0 1 3 3v1h1a3 3 0 0 1 3 3v7a2 2 0 0 1-2 2h-2v1a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3v-1H5a2 2 0 0 1-2-2v-7a3 3 0 0 1 3-3h1v-1a3 3 0 0 1 3-3zm-8 12a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1zm14-22.75A3.75 3.75 0 0 0 27.75 19H40v22a3 3 0 0 1-3 3H23a4 4 0 0 0 4-4v-7a5 5 0 0 0-4.084-4.916A5 5 0 0 0 18 24h-8c-.711 0-1.387.15-2 .417V7a3 3 0 0 1 3-3h13zM10 28a1 1 0 0 0-1 1v1h10v-1a1 1 0 0 0-1-1zm29.462-11.5H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
