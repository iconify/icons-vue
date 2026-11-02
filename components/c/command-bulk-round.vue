<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg1h1q77m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:command-bulk-round" /></template>
<style>
.qg1h1q77m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 10a4 4 0 1 1 4-4v2h4V6a4 4 0 1 1 4 4h-2v4h2a4 4 0 1 1-4 4v-2h-4v2a4 4 0 1 1-4-4h2v-4Z");
}

</style>
