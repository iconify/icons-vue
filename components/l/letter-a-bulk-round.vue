<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwlfc3bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-a-bulk-round" /></template>
<style>
.dwlfc3bdk {
  fill: currentColor;
  d: path("M6 14V8a6 6 0 1 1 12 0v12a1 1 0 0 1-2 0v-5H8v5a1 1 0 0 1-2 0Zm2-1h8V8a4 4 0 0 0-8 0Z");
}

</style>
