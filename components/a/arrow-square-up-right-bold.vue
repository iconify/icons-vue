<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dg79cac0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-square-up-right-bold" /></template>
<style>
.dg79cac0d {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 176H52V52h152ZM87.51 168.49a12 12 0 0 1 0-17L131 108h-19a12 12 0 0 1 0-24h48a12 12 0 0 1 12 12v48a12 12 0 0 1-24 0v-19l-43.51 43.52a12 12 0 0 1-17 0Z");
}

</style>
