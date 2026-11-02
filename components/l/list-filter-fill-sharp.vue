<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m538sebkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-filter-fill-sharp" /></template>
<style>
.m538sebkk {
  fill: currentColor;
  d: path("M4 5h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m3 6h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m3 6h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

</style>
