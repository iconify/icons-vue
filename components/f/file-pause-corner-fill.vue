<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iujbohbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-pause-corner-fill" /></template>
<style>
.iujbohbxu {
  fill: currentColor;
  d: path("M19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10m-6-6v2a2 2 0 0 0 2 2h2Zm3 9v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0m4 0v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0");
}

</style>
