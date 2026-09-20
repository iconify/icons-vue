<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gb3s7_bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-rotate-counterclockwise-20-regular" /></template>
<style>
.gb3s7_bph {
  fill: currentColor;
  d: path("M10 3a7 7 0 0 1 7 7a.5.5 0 0 1-1 0a6 6 0 0 0-12 0a5.99 5.99 0 0 0 3 5.191V13a.5.5 0 0 1 1 0v3.5a.5.5 0 0 1-.5.5H4a.5.5 0 0 1 0-1h2.397A7 7 0 0 1 10 3m0 5a2 2 0 1 1 0 4a2 2 0 0 1 0-4m0 1a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
