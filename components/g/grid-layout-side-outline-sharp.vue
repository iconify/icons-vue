<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttqjf1b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-layout-side-outline-sharp" /></template>
<style>
.ttqjf1b4r {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h8V5H5zm14 0V5h-4v14z");
}

</style>
