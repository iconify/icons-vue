<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz2iag7bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-conveyor-fill" /></template>
<style>
.kz2iag7bw {
  fill: currentColor;
  d: path("M8 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v3h1a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h1Zm6 3V4h-4v2ZM9 9v2a1 1 0 0 0 2 0V9a1 1 0 0 0-2 0m4 0v2a1 1 0 0 0 2 0V9a1 1 0 0 0-2 0M2 18a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm2 0v2h16v-2Z");
}

</style>
