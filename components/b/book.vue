<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f8d0hn3sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:book" /></template>
<style>
.f8d0hn3sv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.7 4.5h-2.3c-2.2 0-4 1.8-4 4v31c0 2.2 1.8 4 4 4h2.3m0-39v39h20.9c2.2 0 4-1.8 4-4v-31c0-2.2-1.8-4-4-4z");
}

</style>
