<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivz-z2btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:briefcase-plus" /></template>
<style>
.ivz-z2btf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 19.5H2.5V6h18v6.2M8.5 6V4a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2m3.5 9v6m-3-3h6");
}

</style>
