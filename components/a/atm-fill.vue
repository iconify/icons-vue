<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s99j0dz2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:atm-fill" /></template>
<style>
.s99j0dz2b {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a1 1 0 0 1-2 0v-6h-2v8a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-8H4v6a1 1 0 0 1-2 0Zm18 4V5a1 1 0 0 0-1-1H5a.997.997 0 0 0-1 1v4Zm-3-4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM9 16a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
