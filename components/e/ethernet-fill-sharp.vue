<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmoc0ybje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ethernet-fill-sharp" /></template>
<style>
.xmoc0ybje {
  fill: currentColor;
  d: path("M3 3h18a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1h-3v3a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1v-3H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m4 5a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 0a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm4 3V8a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m4-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Z");
}

</style>
