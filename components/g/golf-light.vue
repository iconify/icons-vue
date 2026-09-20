<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h96-o1bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:golf-light" /></template>
<style>
.h96-o1bkb {
  fill: currentColor;
  d: path("M174 100a10 10 0 1 1-10-10a10 10 0 0 1 10 10m-42 22a10 10 0 1 0 10 10a10 10 0 0 0-10-10m82-26a86 86 0 1 1-86-86a86.1 86.1 0 0 1 86 86m-12 0a74 74 0 1 0-74 74a74.09 74.09 0 0 0 74-74m-36.14 98.4c-13.38 5.11-25.77 7.6-37.86 7.6s-24.48-2.49-37.86-7.6a6 6 0 1 0-4.28 11.2a122.3 122.3 0 0 0 36.14 8.21V248a6 6 0 0 0 12 0v-34.19a122.3 122.3 0 0 0 36.14-8.21a6 6 0 0 0-4.28-11.2");
}

</style>
