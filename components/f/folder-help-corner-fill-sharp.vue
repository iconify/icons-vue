<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqaq703gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-help-corner-fill-sharp" /></template>
<style>
.gqaq703gs {
  fill: currentColor;
  d: path("M3 3h7c.265 0 .52.105.707.293L12.414 5H21a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m11 13a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 16 16a1 1 0 0 1-2 0m3 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
