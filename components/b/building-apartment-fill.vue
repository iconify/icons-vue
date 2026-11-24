<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdxn09k9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-apartment-fill" /></template>
<style>
.wdxn09k9s {
  fill: currentColor;
  d: path("M9 19v3H3a1 1 0 0 1-1-1v-8a3 3 0 0 1 3-3h1V6a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v4h1a3 3 0 0 1 3 3v8a1 1 0 0 1-1 1h-6v-3a3 3 0 1 0-6 0m1.01-12H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M10 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M6 20v-8H5a.997.997 0 0 0-1 1v7Zm12 0h2v-7a1 1 0 0 0-1-1h-1Zm-7 2v-3a1 1 0 0 1 2 0v3Z");
}

</style>
