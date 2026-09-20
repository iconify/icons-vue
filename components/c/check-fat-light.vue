<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dxv-rfshs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:check-fat-light" /></template>
<style>
.dxv-rfshs {
  fill: currentColor;
  d: path("m241.87 69.66l-24-23.56a14 14 0 0 0-19.77 0L104 139l-38.1-36.9a14 14 0 0 0-19.8 0l-24 24a14 14 0 0 0 0 19.79l71.62 72a14 14 0 0 0 19.8 0L241.91 89.5a14 14 0 0 0-.04-19.84M233.42 81L105 209.41a2 2 0 0 1-2.81 0l-71.62-72a2 2 0 0 1 0-2.82l24-24A2 2 0 0 1 56 110a2.12 2.12 0 0 1 1.5.64l42.35 41.08a6 6 0 0 0 8.39 0l98.37-97.11a2 2 0 0 1 2.87 0l24 23.56a2 2 0 0 1-.06 2.83");
}

</style>
