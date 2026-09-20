<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h6vlvbcat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:intersection-bold" /></template>
<style>
.h6vlvbcat {
  fill: currentColor;
  d: path("M212 120v80a12 12 0 0 1-24 0v-80a60 60 0 0 0-120 0v80a12 12 0 0 1-24 0v-80a84 84 0 0 1 168 0");
}

</style>
