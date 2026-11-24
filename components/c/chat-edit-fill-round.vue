<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x98s3ny7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-edit-fill-round" /></template>
<style>
.x98s3ny7j {
  fill: currentColor;
  d: path("M9 18c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5Zm-1-7v2a1 1 0 0 0 1 1h2c.265 0 .52-.105.707-.293l4-4a1 1 0 0 0 0-1.414l-2-2a.997.997 0 0 0-1.414 0l-4 4A1 1 0 0 0 8 11");
}

</style>
