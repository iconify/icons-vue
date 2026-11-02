<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-_a7rgxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headset-fill-sharp" /></template>
<style>
.i-_a7rgxz {
  fill: currentColor;
  d: path("M6.082 9H8a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1h1.061a8.002 8.002 0 0 1 15.878 0H21a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1h-8a1 1 0 0 1 0-2h7v-2h-4a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1h1.918A6.002 6.002 0 0 0 6.082 9");
}

</style>
