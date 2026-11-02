<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7sqtnbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fridge-fill-round" /></template>
<style>
.h7sqtnbqt {
  fill: currentColor;
  d: path("M9 2h6a5 5 0 0 1 5 5v2H4V7a5 5 0 0 1 5-5m7 4a1 1 0 0 0-2 0v1a1 1 0 0 0 2 0Zm4 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5v-6Zm-4 6v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0");
}

</style>
