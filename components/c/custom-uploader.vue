<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xai-g_b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:custom-uploader" /></template>
<style>
.xai-g_b2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33 24l-8.935 6.187L15 24l9 18zm3-6l6-12l-18 8L6 6l6 12l12 5.29zm-21 6l-3-6m24 0l-3 6");
}

</style>
