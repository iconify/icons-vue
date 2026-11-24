<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmt9ndc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-corner-fill-round" /></template>
<style>
.zmt9ndc2s {
  fill: currentColor;
  d: path("M19 10h-6a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10m-6-4a2 2 0 0 0 2 2h2l-4-4Zm1 6h6a2 2 0 0 1 2 2v2c-.001 3.075-1.94 4.852-4.629 5.928a1 1 0 0 1-.742 0C13.94 20.852 12.001 19.075 12 16v-2a2 2 0 0 1 2-2");
}

</style>
