<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk37-nbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-office-fill-round" /></template>
<style>
.qk37-nbjd {
  fill: currentColor;
  d: path("M15 22v-3a3 3 0 1 0-6 0v3H4a1 1 0 0 1-1-1V9a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v12a1 1 0 0 1-1 1Zm-6-9V9a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4 0V9a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m4-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm-6 13v-3a1 1 0 0 1 2 0v3Z");
}

</style>
