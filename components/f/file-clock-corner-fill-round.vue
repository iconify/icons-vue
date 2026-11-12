<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6gse5mtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-clock-corner-fill-round" /></template>
<style>
.a6gse5mtt {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-6a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 6a2 2 0 0 0 2 2h2l-4-4Zm-2 11a6 6 0 1 1 12 0a6 6 0 0 1-12 0m2 0a4 4 0 1 0 8 0a4 4 0 0 0-8 0m5-2v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0");
}

</style>
