<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqlogbb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:city-fill-sharp" /></template>
<style>
.aqlogbb8b {
  fill: currentColor;
  d: path("M8 8V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v9h5a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1Zm4-2a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-4 4H4v10h4Zm4 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-6 2h.01a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m6.01 2H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M16 20h4v-6h-4ZM6 16h.01a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m12 0h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>
