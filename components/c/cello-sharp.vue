<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cenns98mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cello-sharp" /></template>
<style>
.cenns98mz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5c3.6 0 4.25 1.4 4.25 3.25C16.25 11.2 15 11.9 15 13s3 1.9 3 4c0 1.6-2.5 2.5-6 2.5s-6-.9-6-2.5c0-2.1 3-2.9 3-4s-1.25-1.8-1.25-3.25C7.75 7.9 8.4 6.5 12 6.5Zm0 0V2.75m0 16.75v1.75m-1.75-7v2.5m3.5-2.5v2.5");
}

</style>
