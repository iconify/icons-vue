<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdp40bc3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:insert-chart-sharp" /></template>
<style>
.fdp40bc3b {
  fill: currentColor;
  d: path("M7.73 16.5h1v-6h-1zm3.77 0h1v-9h-1zm3.77 0h1v-3h-1zM4 20V4h16v16z");
}

</style>
