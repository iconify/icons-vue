<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omecsnbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-clock-corner-fill" /></template>
<style>
.omecsnbif {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM17 8l-4-4v2a2 2 0 0 0 2 2Zm-6 9a6 6 0 1 1 12 0a6 6 0 0 1-12 0m2 0a4 4 0 1 0 8 0a4 4 0 0 0-8 0m5-2v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0");
}

</style>
