<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l54gbmbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-vertical-fill" /></template>
<style>
.l54gbmbru {
  fill: currentColor;
  d: path("M9 6a3 3 0 1 1 6 0v14a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Zm13 4v10a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V10a3 3 0 0 1 6 0M2 13a3 3 0 0 1 6 0v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

</style>
