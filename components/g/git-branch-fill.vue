<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzw5ddb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-branch-fill" /></template>
<style>
.lzw5ddb4k {
  fill: currentColor;
  d: path("M6 8.829v2.342A3 3 0 0 1 7 11h10a1 1 0 0 0 1-1V8.829a3 3 0 1 1 2 0V10a3 3 0 0 1-3 3H7a.997.997 0 0 0-1 1v1.171a3 3 0 1 1-2 0V8.829a3 3 0 1 1 2 0");
}

</style>
