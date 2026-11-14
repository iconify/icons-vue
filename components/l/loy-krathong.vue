<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2jc14bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loy-krathong" /></template>
<style>
.v2jc14bhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 12.5l3.5-3l2.5 3L12 10l2.5 2.5l2.5-3l3.5 3c-1 3-4.5 4.5-8.5 4.5s-7.5-1.5-8.5-4.5Zm0 8.5c2-1.25 4-1.25 5.75 0s3.75 1.25 5.5 0s3.75-1.25 5.75 0M12 2.5C14 4.75 14 7 12 7s-2-2.25 0-4.5Z");
}

</style>
