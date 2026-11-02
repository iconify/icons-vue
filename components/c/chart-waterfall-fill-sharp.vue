<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-93nccvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-waterfall-fill-sharp" /></template>
<style>
.i-93nccvc {
  fill: currentColor;
  d: path("M4 4v15h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0m8 2v3a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0M8 9v7a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0m8 0v3a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0m4 3v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
