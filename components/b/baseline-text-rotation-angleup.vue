<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w452jz58z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-text-rotation-angleup" /></template>
<style>
.w452jz58z {
  fill: currentColor;
  d: path("M4.49 4.21L3.43 5.27L7.85 16.4l1.48-1.48l-.92-2.19l3.54-3.54l2.19.92l1.48-1.48zm3.09 6.8L5.36 6.14l4.87 2.23zm12.99-1.68h-4.24l1.41 1.41l-8.84 8.84L10.32 21l8.84-8.84l1.41 1.41z");
}

</style>
