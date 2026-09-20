<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w7n8g7ugz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:git-fork-thin" /></template>
<style>
.w7n8g7ugz {
  fill: currentColor;
  d: path("M220 64a28 28 0 1 0-32 27.71V112a12 12 0 0 1-12 12H80a12 12 0 0 1-12-12V91.71a28 28 0 1 0-8 0V112a20 20 0 0 0 20 20h44v32.29a28 28 0 1 0 8 0V132h44a20 20 0 0 0 20-20V91.71A28 28 0 0 0 220 64M44 64a20 20 0 1 1 20 20a20 20 0 0 1-20-20m104 128a20 20 0 1 1-20-20a20 20 0 0 1 20 20m44-108a20 20 0 1 1 20-20a20 20 0 0 1-20 20");
}

</style>
