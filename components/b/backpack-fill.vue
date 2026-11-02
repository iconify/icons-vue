<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxqcyn49p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-fill" /></template>
<style>
.pxqcyn49p {
  fill: currentColor;
  d: path("M9 6V4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2h1a5 5 0 0 1 5 5v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-8a5 5 0 0 1 5-5Zm4-2h-2v2h2Zm3 6H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m-1 9a1 1 0 0 0 2 0v-2a2 2 0 0 0-2-2H9a2 2 0 0 0-2 2v2a1 1 0 0 0 2 0v-2h6Z");
}

</style>
