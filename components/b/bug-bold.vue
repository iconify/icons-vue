<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q0i_tfmdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bug-bold" /></template>
<style>
.q0i_tfmdb {
  fill: currentColor;
  d: path("M140 88a16 16 0 1 1 16 16a16 16 0 0 1-16-16m-40-16a16 16 0 1 0 16 16a16 16 0 0 0-16-16m120 72a91.8 91.8 0 0 1-2.34 20.64l19.15 8.36a12 12 0 0 1-9.62 22l-18-7.85a92 92 0 0 1-162.46 0l-18 7.85a12 12 0 1 1-9.62-22l19.15-8.36A91.8 91.8 0 0 1 36 144v-4H16a12 12 0 0 1 0-24h20v-4a91.8 91.8 0 0 1 2.34-20.64L19.19 83a12 12 0 0 1 9.62-22l18 7.85a92 92 0 0 1 162.46 0l18-7.85a12 12 0 1 1 9.62 22l-19.15 8.36A91.8 91.8 0 0 1 220 112v4h20a12 12 0 0 1 0 24h-20ZM60 116h136v-4a68 68 0 0 0-136 0Zm56 94.92V140H60v4a68.1 68.1 0 0 0 56 66.92M196 144v-4h-56v70.92A68.1 68.1 0 0 0 196 144");
}

</style>
