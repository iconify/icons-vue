<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s9m9j3k-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-pie-light" /></template>
<style>
.s9m9j3k-t {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m74.74 51.92L134 117.61V38.2a90 90 0 0 1 68.74 39.72M122 38.2v86.34L47.24 167.7A90 90 0 0 1 122 38.2m6 179.8a90 90 0 0 1-74.74-39.92l155.5-89.78A90 90 0 0 1 128 218");
}

</style>
