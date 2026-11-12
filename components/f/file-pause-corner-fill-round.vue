<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaumyv2yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pause-corner-fill-round" /></template>
<style>
.kaumyv2yg {
  fill: currentColor;
  d: path("M19 10h-6a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10m-6-6v2a2 2 0 0 0 2 2h2Zm3 17a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Zm2 0v-8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0");
}

</style>
