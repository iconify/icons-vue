<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3753ybvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:castle-fill" /></template>
<style>
.y3753ybvf {
  fill: currentColor;
  d: path("M5 3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v1h2V3a1 1 0 0 1 2 0v7a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-3v-4a4 4 0 0 0-8 0v4H5a3 3 0 0 1-3-3v-6a3 3 0 0 1 3-3Z");
}

</style>
