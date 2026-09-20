<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zrbssrrvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gender-neuter-bold" /></template>
<style>
.zrbssrrvx {
  fill: currentColor;
  d: path("M212 104a84 84 0 1 0-96 83.13V232a12 12 0 0 0 24 0v-44.87A84.12 84.12 0 0 0 212 104m-84 60a60 60 0 1 1 60-60a60.07 60.07 0 0 1-60 60");
}

</style>
