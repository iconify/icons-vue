<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_xg-lbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:courthouse-fill" /></template>
<style>
.t_xg-lbyp {
  fill: currentColor;
  d: path("M21 8h-3v8a2 2 0 0 1 2 2v2h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-2a2 2 0 0 1 2-2V8H3a1 1 0 0 1-.406-1.914l9-4a1 1 0 0 1 .812 0l9 4A1 1 0 0 1 21 8M11 8H8v8h3Zm2 0v8h3V8Z");
}

</style>
