<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc0nr_bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:acacia-tree" /></template>
<style>
.xc0nr_bsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21v-9m-8.5-2C3.5 7 7 6 12 6s8.5 1 8.5 4c0 2-3.5 2.5-8.5 2.5S3.5 12 3.5 10ZM6 21h12");
}

</style>
