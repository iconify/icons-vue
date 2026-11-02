<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsge3c3yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-fork-fill-sharp" /></template>
<style>
.jsge3c3yu {
  fill: currentColor;
  d: path("M6 8.829V11h12V8.829a3 3 0 1 1 2 0V12a1 1 0 0 1-1 1h-6v2.171a3 3 0 1 1-2 0V13H5a1 1 0 0 1-1-1V8.829a3 3 0 1 1 2 0");
}

</style>
