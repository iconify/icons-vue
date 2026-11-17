<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufqvlob5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gas-cylinder-fill-sharp" /></template>
<style>
.ufqvlob5j {
  fill: currentColor;
  d: path("M8 2h8a1 1 0 0 1 1 1v3.099A5.01 5.01 0 0 1 21 11v1H3v-1a5.01 5.01 0 0 1 4-4.901V3a1 1 0 0 1 1-1m7 4V4H9v2ZM3 14h18v5a1 1 0 0 1-1 1h-3v1a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-1H4a1 1 0 0 1-1-1Z");
}

</style>
