<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0armybkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ceiling-light-fill-round" /></template>
<style>
.p0armybkg {
  fill: currentColor;
  d: path("M11 3a1 1 0 0 1 2 0v3.049A10.005 10.005 0 0 1 22 16a1 1 0 0 1-1 1h-4.099a5.003 5.003 0 0 1-9.802 0H3a1 1 0 0 1-1-1c0-5.134 3.892-9.436 9-9.951Zm3.83 14H9.17a3.002 3.002 0 0 0 5.66 0");
}

</style>
