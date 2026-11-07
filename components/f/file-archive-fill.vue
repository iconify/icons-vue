<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyc53ezln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-archive-fill" /></template>
<style>
.tyc53ezln {
  fill: currentColor;
  d: path("M4 21V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3h-2a1 1 0 0 1-1-1v-3a4 4 0 0 0-8-.003V21a1 1 0 0 1-2 0m9-17v3a2 2 0 0 0 2 2h3Zm-2.99 1H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M8 7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm2.01 2H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m-2 2H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M13 18v2a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-2a3 3 0 1 1 6 0m-4 0v2h2v-2a1 1 0 0 0-2 0");
}

</style>
