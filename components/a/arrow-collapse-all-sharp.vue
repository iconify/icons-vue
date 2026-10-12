<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg9piwb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-collapse-all-sharp" /></template>
<style>
.sg9piwb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.75L9.5 9.5m.5-4.25V10H5.25m15 10.25L14.5 14.5m-.5 4.25V14h4.75m1.5-10.25L14.5 9.5M14 5.25V10h4.75m-15 10.25L9.5 14.5m.5 4.25V14H5.25");
}

</style>
