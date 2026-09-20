<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jxtp01gau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-text-extract-48-filled" /></template>
<style>
.jxtp01gau {
  fill: currentColor;
  d: path("M24 15.75A4.25 4.25 0 0 0 28.25 20H40v19.75A4.25 4.25 0 0 1 35.75 44h-23.5A4.25 4.25 0 0 1 8 39.75V33.5h12.75a3.25 3.25 0 0 0 0-6.5H8V8.25A4.25 4.25 0 0 1 12.25 4H24zM16.25 35.5a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zm4.5-6.5a1.25 1.25 0 1 1 0 2.5H5.25a1.25 1.25 0 1 1 0-2.5zm-4.5-6.5a1.25 1.25 0 1 0 0 2.5h15.5a1.25 1.25 0 1 0 0-2.5zM26.5 4.374c.466.21.895.503 1.263.871l10.992 10.992c.368.368.662.797.871 1.263H28.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
