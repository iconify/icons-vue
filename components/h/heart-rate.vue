<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yazmcu-mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-rate" /></template>
<style>
.yazmcu-mu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12S6.6 8.8 6.5 5.25c.1-1.49 1.36-2.75 3-2.75c1 0 1.96.6 2.5 1.5c.54-.9 1.5-1.5 2.5-1.5c1.64 0 2.9 1.26 3 2.75C17.4 8.8 12 12 12 12Zm-9.5 5h5L9 14.75l2 5.75l2-5.5l1.25 2h7.25");
}

</style>
