<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rm-3-q78h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:lock-key-bold" /></template>
<style>
.rm-3-q78h {
  fill: currentColor;
  d: path("M208 76h-28V56a52 52 0 0 0-104 0v20H48a20 20 0 0 0-20 20v112a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V96a20 20 0 0 0-20-20M100 56a28 28 0 0 1 56 0v20h-56Zm104 148H52V100h152Zm-76-92a32 32 0 0 0-12 61.66V180a12 12 0 0 0 24 0v-6.34A32 32 0 0 0 128 112m0 24a8 8 0 1 1-8 8a8 8 0 0 1 8-8");
}

</style>
