<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa6pubb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-f-bulk-sharp" /></template>
<style>
.sa6pubb4r {
  fill: currentColor;
  d: path("M8 5v6h7a1 1 0 0 1 0 2H8v7a1 1 0 0 1-2 0V4a1 1 0 0 1 1-1h10a1 1 0 0 1 0 2Z");
}

</style>
