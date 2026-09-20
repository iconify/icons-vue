<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="psdf7tb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:git-fork-light" /></template>
<style>
.psdf7tb9t {
  fill: currentColor;
  d: path("M222 64a30 30 0 1 0-36 29.4V112a10 10 0 0 1-10 10H80a10 10 0 0 1-10-10V93.4a30 30 0 1 0-12 0V112a22 22 0 0 0 22 22h42v28.6a30 30 0 1 0 12 0V134h42a22 22 0 0 0 22-22V93.4A30.05 30.05 0 0 0 222 64M46 64a18 18 0 1 1 18 18a18 18 0 0 1-18-18m100 128a18 18 0 1 1-18-18a18 18 0 0 1 18 18m46-110a18 18 0 1 1 18-18a18 18 0 0 1-18 18");
}

</style>
