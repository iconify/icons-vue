<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a5ti6fbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-heart-fill" /></template>
<style>
.a5ti6fbda {
  fill: currentColor;
  d: path("M208 32H48a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a16 16 0 0 0 16-16V48a16 16 0 0 0-16-16M104 184H64a8 8 0 0 1 0-16h40a8 8 0 0 1 0 16m-48-56a8 8 0 0 1 8-8h32a8 8 0 0 1 0 16H64a8 8 0 0 1-8-8m105.79 57.58a4 4 0 0 1-3.58 0C156.65 184.8 120 166.17 120 140a22 22 0 0 1 40-12.64A22 22 0 0 1 200 140c0 26.17-36.65 44.8-38.21 45.58M192 88H64a8 8 0 0 1 0-16h128a8 8 0 0 1 0 16");
}

</style>
