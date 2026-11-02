<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfk96160j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-tree-fill-sharp" /></template>
<style>
.kfk96160j {
  fill: currentColor;
  d: path("M5 6v5h3a1 1 0 0 1 0 2H5v4h3a1 1 0 0 1 0 2H4a1 1 0 0 1-1-1V6a1 1 0 0 1 2 0m3-1h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 6h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2m0 6h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
