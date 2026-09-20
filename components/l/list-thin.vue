<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ph8nyqjfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:list-thin" /></template>
<style>
.ph8nyqjfc {
  fill: currentColor;
  d: path("M220 128a4 4 0 0 1-4 4H40a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4M40 68h176a4 4 0 0 0 0-8H40a4 4 0 0 0 0 8m176 120H40a4 4 0 0 0 0 8h176a4 4 0 0 0 0-8");
}

</style>
