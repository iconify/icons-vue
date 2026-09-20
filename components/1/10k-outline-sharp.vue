<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6sf1oxjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:10k-outline-sharp" /></template>
<style>
.h6sf1oxjo {
  fill: currentColor;
  d: path("M6 15h1.5V9H5v1.5h1zm2.5 0H13V9H8.5zm1.5-1.5v-3h1.5v3zm3.925 1.5h1.5v-2.25l1.75 2.25H19l-2.325-3L19 9h-1.825l-1.75 2.25V9h-1.5zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
