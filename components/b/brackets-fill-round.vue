<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id3zm3bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brackets-fill-round" /></template>
<style>
.id3zm3bbq {
  fill: currentColor;
  d: path("M6 8a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2H6a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2Zm12-2a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2Z");
}

</style>
