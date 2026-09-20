<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tn1yfj7xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-left-right-fill" /></template>
<style>
.tn1yfj7xj {
  fill: currentColor;
  d: path("M42.34 85.66a8 8 0 0 1 0-11.32l32-32A8 8 0 0 1 88 48v24h120a8 8 0 0 1 0 16H88v24a8 8 0 0 1-13.66 5.66Zm171.32 84.68l-32-32A8 8 0 0 0 168 144v24H48a8 8 0 0 0 0 16h120v24a8 8 0 0 0 13.66 5.66l32-32a8 8 0 0 0 0-11.32");
}

</style>
