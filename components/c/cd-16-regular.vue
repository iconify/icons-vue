<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w2548cc1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cd-16-regular" /></template>
<style>
.w2548cc1l {
  fill: currentColor;
  d: path("M8 6a2 2 0 1 0 0 4a2 2 0 0 0 0-4M7 8a1 1 0 1 1 2 0a1 1 0 0 1-2 0m1-6a6 6 0 1 0 0 12A6 6 0 0 0 8 2M3 8a5 5 0 1 1 10 0A5 5 0 0 1 3 8");
}

</style>
