<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obtowyb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fire-extinguisher-fill" /></template>
<style>
.obtowyb8m {
  fill: currentColor;
  d: path("M12 7.099V6H9a3 3 0 0 0-3 3v7a1 1 0 0 1-2 0V9a5 5 0 0 1 5-5h3.838l5.846-1.949a1.001 1.001 0 0 1 .632 1.898L14 5.721v1.378A5.01 5.01 0 0 1 18 12v2H8v-2a5.01 5.01 0 0 1 4-4.901M8 19v-3h10v3a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3");
}

</style>
