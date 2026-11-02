<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-6cg7bml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-left-fill" /></template>
<style>
.x-6cg7bml {
  fill: currentColor;
  d: path("M5 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM7 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3Zm0 10a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3Z");
}

</style>
