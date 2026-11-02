<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzjt250kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-dollar-fill-round" /></template>
<style>
.bzjt250kh {
  fill: currentColor;
  d: path("M13 3v1h1c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 18 8a1 1 0 0 1-2 0a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h4a4 4 0 0 1 4 4v1a4 4 0 0 1-4 4h-1v1a1 1 0 0 1-2 0v-1h-1a3.98 3.98 0 0 1-2.828-1.172A3.98 3.98 0 0 1 6 16a1 1 0 0 1 2 0a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-1a2 2 0 0 0-2-2h-4a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4h1V3a1 1 0 0 1 2 0");
}

</style>
