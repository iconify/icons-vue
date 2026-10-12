<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy3_ypbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:list-collapse-sharp" /></template>
<style>
.yy3_ypbzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 5.5h9.5m-9.5 6.5h9.5m-9.5 6.5h9.5M3.75 5.25L6 7.5l2.25-2.25m-4.5 13.5L6 16.5l2.25 2.25");
}

</style>
