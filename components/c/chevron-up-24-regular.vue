<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzv_4nv8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-24-regular" /></template>
<style>
.mzv_4nv8b {
  fill: currentColor;
  d: path("M4.22 15.53a.75.75 0 0 0 1.06 0L12 8.81l6.72 6.72a.75.75 0 1 0 1.06-1.06l-7.25-7.25a.75.75 0 0 0-1.06 0l-7.25 7.25a.75.75 0 0 0 0 1.06");
}

</style>
