<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k746_4bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apothecary-drawers" /></template>
<style>
.k746_4bno {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14v19H5Zm0 6.25h14m-14 6.5h14M12 2.5v19M8.5 5.75h.01m6.99 0h.01M8.5 12h.01m6.99 0h.01M8.5 18.5h.01m6.99 0h.01");
}

</style>
