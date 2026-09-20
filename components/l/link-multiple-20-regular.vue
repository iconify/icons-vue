<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="njx_x96ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-multiple-20-regular" /></template>
<style>
.njx_x96ue {
  fill: currentColor;
  d: path("M1 8a4 4 0 0 1 4-4h6a4 4 0 0 1 0 8H9.5a.5.5 0 0 1 0-1H11a3 3 0 1 0 0-6H5a3 3 0 0 0-.872 5.871a5 5 0 0 0-.126 1.003A4 4 0 0 1 1 8m17 4a3 3 0 0 0-2.128-2.871q.113-.487.127-1.003A4.002 4.002 0 0 1 15 16H9a4 4 0 0 1 0-8h1.5a.5.5 0 0 1 0 1H9a3 3 0 1 0 0 6h6a3 3 0 0 0 3-3");
}

</style>
