<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8p-h-95k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-fill-round" /></template>
<style>
.e8p-h-95k {
  fill: currentColor;
  d: path("M4 4v9.586l1.293-1.293a3.826 3.826 0 0 1 5.414 0a1.83 1.83 0 0 0 2.586 0l7-7a.999.999 0 1 1 1.414 1.414l-7 7a3.826 3.826 0 0 1-5.414 0a1.83 1.83 0 0 0-2.586 0L4.025 16.39A3 3 0 0 0 7 19h14a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0");
}

</style>
