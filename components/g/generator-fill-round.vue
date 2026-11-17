<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb8xq7qis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:generator-fill-round" /></template>
<style>
.zb8xq7qis {
  fill: currentColor;
  d: path("M9 2h6a5.006 5.006 0 0 1 4.928 4.146A3.005 3.005 0 0 1 22 9v8a3 3 0 0 1-3 3v1a1 1 0 0 1-2 0v-1H7v1a1 1 0 0 1-2 0v-1a3 3 0 0 1-3-3V9c0-1.298.838-2.451 2.072-2.854A5.01 5.01 0 0 1 9 2m6 2H9a3 3 0 0 0-2.83 2h11.66A3.01 3.01 0 0 0 15 4m-6.586 8l1.293-1.293a.999.999 0 1 0-1.414-1.414l-3 3A1 1 0 0 0 6 14h1.586l-1.293 1.293a.999.999 0 1 0 1.414 1.414l3-3A1 1 0 0 0 10 12ZM17 10h-3a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2m-3 4a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2Z");
}

</style>
