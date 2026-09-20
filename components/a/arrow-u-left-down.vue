<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lxpvh1boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-u-left-down" /></template>
<style>
.lxpvh1boe {
  fill: currentColor;
  d: path("M208 88v88a8 8 0 0 1-16 0V88a48 48 0 0 0-96 0v116.69l34.34-34.35a8 8 0 0 1 11.32 11.32l-48 48a8 8 0 0 1-11.32 0l-48-48a8 8 0 0 1 11.32-11.32L80 204.69V88a64 64 0 0 1 128 0");
}

</style>
