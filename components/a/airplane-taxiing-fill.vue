<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="udcn3kjqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:airplane-taxiing-fill" /></template>
<style>
.udcn3kjqh {
  fill: currentColor;
  d: path("M248 136v24a8 8 0 0 1-8 8H61.07a39.75 39.75 0 0 1-38.31-28.51L8.69 92.6A16 16 0 0 1 24 72h8a8 8 0 0 1 5.65 2.34L59.32 96h22.49l-9-26.94A16 16 0 0 1 88 48h8a8 8 0 0 1 5.66 2.34L147.32 96H208a40 40 0 0 1 40 40m-40 48a16 16 0 1 0 16 16a16 16 0 0 0-16-16m-96 0a16 16 0 1 0 16 16a16 16 0 0 0-16-16");
}

</style>
