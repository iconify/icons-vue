<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh7km5m1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-heatmap-fill-sharp" /></template>
<style>
.dh7km5m1y {
  fill: currentColor;
  d: path("M11 2v9H2V3a1 1 0 0 1 1-1Zm2 9V2h8a1 1 0 0 1 1 1v8ZM5.158 6.221a2 2 0 1 0 3.684 1.558A2 2 0 0 0 5.158 6.22M17 8h.01a1 1 0 0 0 0-2H17a1 1 0 0 0 0 2m-6 5v9H3a1 1 0 0 1-1-1v-8Zm11 0v8a1 1 0 0 1-1 1h-8v-9Zm-6.842 3.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558");
}

</style>
