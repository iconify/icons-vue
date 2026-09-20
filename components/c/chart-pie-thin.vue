<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o79_kmw4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-pie-thin" /></template>
<style>
.o79_kmw4n {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m77.58 50.59L132 121.07v-85a92.07 92.07 0 0 1 73.58 42.52M124 36.09v89.6l-77.58 44.79A92 92 0 0 1 124 36.09M128 220a92 92 0 0 1-77.58-42.59l159.16-91.89A92 92 0 0 1 128 220");
}

</style>
