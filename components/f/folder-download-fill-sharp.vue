<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbp-7t7-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-download-fill-sharp" /></template>
<style>
.bbp-7t7-t {
  fill: currentColor;
  d: path("M10 3c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Zm1.293 13.707a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L13 13.586V10a1 1 0 0 0-2 0v3.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414Z");
}

</style>
