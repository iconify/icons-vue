<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c-534ywwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:baby-carriage-fill" /></template>
<style>
.c-534ywwz {
  fill: currentColor;
  d: path("M215.58 54.55a7.5 7.5 0 0 0-1.32-1.27A79.68 79.68 0 0 0 160 32h-8a16 16 0 0 0-16 16v56H55.2A40.07 40.07 0 0 0 16 72a8 8 0 0 0 0 16a24 24 0 0 1 24 24a80.09 80.09 0 0 0 80 80h40a79.94 79.94 0 0 0 55.58-137.45m-6.91 16A63.73 63.73 0 0 1 223.48 104h-56.67ZM160 48a63.6 63.6 0 0 1 36.69 11.61L152 95.35V48Zm-56 176a16 16 0 1 1-16-16a16 16 0 0 1 16 16m104 0a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
