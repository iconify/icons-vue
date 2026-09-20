<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xmiibybeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hurricane-fill" /></template>
<style>
.xmiibybeo {
  fill: currentColor;
  d: path("m158.32 45.36l9.41-35.3a8 8 0 0 0-9.41-9.88a195.9 195.9 0 0 0-58.65 25.09C60.63 50.37 40 85.89 40 128a88.11 88.11 0 0 0 57.68 82.64l-9.41 35.3a8 8 0 0 0 9.41 9.88a195.9 195.9 0 0 0 58.65-25.09C195.37 205.63 216 170.11 216 128a88.1 88.1 0 0 0-57.68-82.64M128 152a24 24 0 1 1 24-24a24 24 0 0 1-24 24");
}

</style>
