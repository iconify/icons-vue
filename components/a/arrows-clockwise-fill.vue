<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m9t6jsulo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-clockwise-fill" /></template>
<style>
.m9t6jsulo {
  fill: currentColor;
  d: path("M224 48v48a8 8 0 0 1-8 8h-48a8 8 0 0 1-5.66-13.66L180.65 72a79.48 79.48 0 0 0-54.72-22.09h-.45a79.52 79.52 0 0 0-55.89 22.8a8 8 0 0 1-11.18-11.44A96 96 0 0 1 192 60.7l18.36-18.36A8 8 0 0 1 224 48m-37.59 135.29a80 80 0 0 1-111.06.71l18.31-18.31A8 8 0 0 0 88 152H40a8 8 0 0 0-8 8v48a8 8 0 0 0 13.66 5.66L64 195.3a95.42 95.42 0 0 0 66 26.76h.53a95.36 95.36 0 0 0 67.07-27.33a8 8 0 0 0-11.18-11.44Z");
}

</style>
