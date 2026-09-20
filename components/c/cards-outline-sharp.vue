<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrr_hacww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cards-outline-sharp" /></template>
<style>
.yrr_hacww {
  fill: currentColor;
  d: path("M6 11.5V6h5.5v5.5zM6 18v-5.5h5.5V18zm6.5-6.5V6H18v5.5zm0 6.5v-5.5H18V18zM8 9.5h1.5V8H8zm6.5 0H16V8h-1.5zM8 16h1.5v-1.5H8zm6.5 0H16v-1.5h-1.5zM3 21V3h18v18zm2-2h14V5H5z");
}

</style>
