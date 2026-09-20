<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z5v6yjw9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:baby-carriage" /></template>
<style>
.z5v6yjw9c {
  fill: currentColor;
  d: path("M160 32h-8a16 16 0 0 0-16 16v56H55.2A40.07 40.07 0 0 0 16 72a8 8 0 0 0 0 16a24 24 0 0 1 24 24a80.09 80.09 0 0 0 80 80h40a80 80 0 0 0 0-160m63.48 72h-56.67l41.86-33.49A63.73 63.73 0 0 1 223.48 104M160 48a63.6 63.6 0 0 1 36.69 11.61L152 95.35V48Zm0 128h-40a64.09 64.09 0 0 1-63.5-56h167a64.09 64.09 0 0 1-63.5 56m-56 48a16 16 0 1 1-16-16a16 16 0 0 1 16 16m104 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
