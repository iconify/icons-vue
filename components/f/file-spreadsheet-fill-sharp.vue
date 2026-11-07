<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feex2ivox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-spreadsheet-fill-sharp" /></template>
<style>
.feex2ivox {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Zm-5 2a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-6a1 1 0 0 0-1-1Zm2 2v1H9v-1Zm2 1v-1h3v1Zm-2 2v1H9v-1Zm2 1v-1h3v1Z");
}

</style>
