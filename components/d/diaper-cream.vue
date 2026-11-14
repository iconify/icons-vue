<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhkmbt-7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diaper-cream" /></template>
<style>
.uhkmbt-7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.654 17.232q-.09.617-.154 1.268H9c-.5-5-2-8.5-6-9v-5h16.5v5c-1.961.245-3.321 1.211-4.257 2.722M3 7.5h16.5M16 15h5l-1 4.5h-3Zm1 4.5h3v2h-3Z");
}

</style>
