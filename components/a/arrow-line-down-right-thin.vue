<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jivsm_bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-down-right-thin" /></template>
<style>
.jivsm_bhl {
  fill: currentColor;
  d: path("M220 40a4 4 0 0 1-4 4H40a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4m-28 60a4 4 0 0 0-4 4v86.34L82.83 85.17a4 4 0 0 0-5.66 5.66L182.34 196H96a4 4 0 0 0 0 8h96a4 4 0 0 0 4-4v-96a4 4 0 0 0-4-4");
}

</style>
