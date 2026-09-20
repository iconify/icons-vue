<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yfmq6yblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-scatter" /></template>
<style>
.yfmq6yblk {
  fill: currentColor;
  d: path("M232 208a8 8 0 0 1-8 8H32a8 8 0 0 1-8-8V48a8 8 0 0 1 16 0v152h184a8 8 0 0 1 8 8m-100-48a12 12 0 1 0-12-12a12 12 0 0 0 12 12m-24-56a12 12 0 1 0-12-12a12 12 0 0 0 12 12m-32 72a12 12 0 1 0-12-12a12 12 0 0 0 12 12m96-48a12 12 0 1 0-12-12a12 12 0 0 0 12 12m24-40a12 12 0 1 0-12-12a12 12 0 0 0 12 12m-20 76a12 12 0 1 0 12-12a12 12 0 0 0-12 12");
}

</style>
