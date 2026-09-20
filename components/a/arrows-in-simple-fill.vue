<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q40nnbtcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-in-simple-fill" /></template>
<style>
.q40nnbtcw {
  fill: currentColor;
  d: path("M120 144v48a8 8 0 0 1-13.66 5.66L88 179.31l-34.34 34.35a8 8 0 0 1-11.32-11.32L76.69 168l-18.35-18.34A8 8 0 0 1 64 136h48a8 8 0 0 1 8 8m93.66-101.66a8 8 0 0 0-11.32 0L168 76.69l-18.34-18.35A8 8 0 0 0 136 64v48a8 8 0 0 0 8 8h48a8 8 0 0 0 5.66-13.66L179.31 88l34.35-34.34a8 8 0 0 0 0-11.32");
}

</style>
