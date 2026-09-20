<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsp_7obwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:empty-dashboard-outline-sharp" /></template>
<style>
.tsp_7obwa {
  fill: currentColor;
  d: path("M6 18h5.5v-4H6zm0-5h5.5V6H6zm6.5 5H18v-7h-5.5zm0-8H18V6h-5.5zM3 21V3h18v4h2v2h-2v2h2v2h-2v2h2v2h-2v4zm2-2h14V5H5zM5 5v14z");
}

</style>
