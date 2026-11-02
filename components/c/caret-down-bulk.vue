<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-ruhhae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-down-bulk" /></template>
<style>
.w8-ruhhae {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 9h8a1.002 1.002 0 0 1 .707 1.707l-4 4a1 1 0 0 1-1.414 0l-4-4A1 1 0 0 1 8 9");
}

</style>
