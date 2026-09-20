<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wlidtxnyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cursor-text-fill" /></template>
<style>
.wlidtxnyk {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16m-64 88a8 8 0 0 1 0 16h-8v24a16 16 0 0 0 16 16h8a8 8 0 0 1 0 16h-8a31.92 31.92 0 0 1-24-10.87A31.92 31.92 0 0 1 104 192h-8a8 8 0 0 1 0-16h8a16 16 0 0 0 16-16v-24h-8a8 8 0 0 1 0-16h8V96a16 16 0 0 0-16-16h-8a8 8 0 0 1 0-16h8a31.92 31.92 0 0 1 24 10.87A31.92 31.92 0 0 1 152 64h8a8 8 0 0 1 0 16h-8a16 16 0 0 0-16 16v24Z");
}

</style>
