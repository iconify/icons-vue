<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y221r7b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cell-signal-medium" /></template>
<style>
.y221r7b6t {
  fill: currentColor;
  d: path("M128 112v88a8 8 0 0 1-16 0v-88a8 8 0 0 1 16 0m-48 32a8 8 0 0 0-8 8v48a8 8 0 0 0 16 0v-48a8 8 0 0 0-8-8m-40 40a8 8 0 0 0-8 8v8a8 8 0 0 0 16 0v-8a8 8 0 0 0-8-8");
}

</style>
