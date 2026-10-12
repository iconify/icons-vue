<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiw4hzsdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dew-point-sharp" /></template>
<style>
.xiw4hzsdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15.45V3.85h4v11.6a3.25 3.25 0 1 1-4 0Zm11.22-8.56l-3.48 6.63a4.25 4.25 0 1 0 7.52 0l-3.48-6.63l-.28-.53z");
}

</style>
