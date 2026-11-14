<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umwbl_g6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-sealant" /></template>
<style>
.umwbl_g6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12.5c-1.5-1.5-6-2-6 1.5c0 1.75.75 2.5 1.25 4.25l.5 2c.25 1 1.25 1 1.5 0l1-2.5c.25-.75 3.25-.75 3.5 0l1 2.5c.25 1 1.25 1 1.5 0l.5-2C17.25 16.5 18 15.75 18 14c0-3.5-4.5-3-6-1.5Zm0-9.75C11 4.25 9.75 5.5 9.75 6.5a2.25 2.25 0 0 0 4.5 0c0-1-1.25-2.25-2.25-3.75Z");
}

</style>
