<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ipc4283ul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-square-in-thin" /></template>
<style>
.ipc4283ul {
  fill: currentColor;
  d: path("M124 136v64a4 4 0 0 1-8 0v-54.34l-73.17 73.17a4 4 0 0 1-5.66-5.66L110.34 140H56a4 4 0 0 1 0-8h64a4 4 0 0 1 4 4m84-100H80a12 12 0 0 0-12 12v48a4 4 0 0 0 8 0V48a4 4 0 0 1 4-4h128a4 4 0 0 1 4 4v128a4 4 0 0 1-4 4h-48a4 4 0 0 0 0 8h48a12 12 0 0 0 12-12V48a12 12 0 0 0-12-12");
}

</style>
