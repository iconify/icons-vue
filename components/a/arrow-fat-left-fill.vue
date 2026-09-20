<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b3tafab2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-left-fill" /></template>
<style>
.b3tafab2j {
  fill: currentColor;
  d: path("M224 88v80a16 16 0 0 1-16 16h-80v40a8 8 0 0 1-13.66 5.66l-96-96a8 8 0 0 1 0-11.32l96-96A8 8 0 0 1 128 32v40h80a16 16 0 0 1 16 16");
}

</style>
