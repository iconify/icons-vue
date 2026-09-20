<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2enkhqtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:8k-outline-sharp" /></template>
<style>
.y2enkhqtx {
  fill: currentColor;
  d: path("M13 15h1.5v-2.25L16.25 15h1.825l-2.325-3l2.325-3H16.25l-1.75 2.25V9H13zm-6.5 0H11V9H6.5zM8 11.5V10h1.5v1.5zM8 14v-1.5h1.5V14zm-5 7V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
