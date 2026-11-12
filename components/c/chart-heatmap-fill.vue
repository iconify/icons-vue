<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw1kjtubw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-heatmap-fill" /></template>
<style>
.bw1kjtubw {
  fill: currentColor;
  d: path("M11 2v9H2V5a3 3 0 0 1 3-3Zm2 9V2h6a3 3 0 0 1 3 3v6ZM5.158 6.221a2 2 0 1 0 3.684 1.558A2 2 0 0 0 5.158 6.22M17 8h.01a1 1 0 0 0 0-2H17a1 1 0 0 0 0 2m-6 5v9H5a3 3 0 0 1-3-3v-6Zm11 0v6a3 3 0 0 1-3 3h-6v-9Zm-6.842 3.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558");
}

</style>
