<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ff9eo5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:1k-plus-sharp" /></template>
<style>
.c5ff9eo5b {
  fill: currentColor;
  d: path("M16.5 14h1v-1.5H19v-1h-1.5V10h-1v1.5H15v1h1.5zm-6 1H12v-2.25L13.75 15h1.75l-2.25-3l2.25-3h-1.75L12 11.25V9h-1.5zm-3 0H9V9H6v1.5h1.5zM3 21V3h18v18z");
}

</style>
