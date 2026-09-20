<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gxc4wu1lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reset-20-regular" /></template>
<style>
.gxc4wu1lz {
  fill: currentColor;
  d: path("M5.854 2.646a.5.5 0 0 1 0 .708L4.207 5H11a6 6 0 1 1-6 6a.5.5 0 0 1 1 0a5 5 0 1 0 5-5H4.207l1.647 1.646a.5.5 0 1 1-.708.708l-2.5-2.5a.5.5 0 0 1 0-.708l2.5-2.5a.5.5 0 0 1 .708 0");
}

</style>
