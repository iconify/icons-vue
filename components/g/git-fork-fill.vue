<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s--6czbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-fork-fill" /></template>
<style>
.s--6czbuf {
  fill: currentColor;
  d: path("M6 8.829V10a.997.997 0 0 0 1 1h10a1 1 0 0 0 1-1V8.829a3 3 0 1 1 2 0V10a3 3 0 0 1-3 3h-4v2.171a3 3 0 1 1-2 0V13H7a3 3 0 0 1-3-3V8.829a3 3 0 1 1 2 0");
}

</style>
