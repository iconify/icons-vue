<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qhcgottio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-centered" /></template>
<style>
.qhcgottio {
  fill: currentColor;
  d: path("M216 40H40a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h60.43l13.68 23.94a16 16 0 0 0 27.78 0L155.57 200H216a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16m0 144h-65.07a8 8 0 0 0-7 4l-16 28l-16-28a8 8 0 0 0-7-4H40V56h176Z");
}

</style>
