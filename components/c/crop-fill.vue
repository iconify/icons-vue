<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klj4fkr8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crop-fill" /></template>
<style>
.klj4fkr8b {
  fill: currentColor;
  d: path("M7 3v13a1 1 0 0 0 1 1h13a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H8a3 3 0 0 1-3-3V7H3a1 1 0 0 1 0-2h2V3a1 1 0 0 1 2 0m3 2h6a3 3 0 0 1 3 3v6a1 1 0 0 1-2 0V8a1 1 0 0 0-1-1h-6a1 1 0 0 1 0-2");
}

</style>
