<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="th74q7c9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chat-teardrop-text-thin" /></template>
<style>
.th74q7c9j {
  fill: currentColor;
  d: path("M168 112a4 4 0 0 1-4 4H96a4 4 0 0 1 0-8h68a4 4 0 0 1 4 4m-4 28H96a4 4 0 0 0 0 8h68a4 4 0 0 0 0-8m64-16a96.11 96.11 0 0 1-96 96H48a12 12 0 0 1-12-12v-84a96 96 0 0 1 192 0m-8 0a88 88 0 0 0-176 0v84a4 4 0 0 0 4 4h84a88.1 88.1 0 0 0 88-88");
}

</style>
