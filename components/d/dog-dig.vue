<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6lj66b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-dig" /></template>
<style>
.e6lj66b9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3h5M12 3v5.5m-3 0h6V13l-3 4.5L9 13ZM2.5 21C5 18.5 8 17.5 12 17.5s7 1 9.5 3.5M6 14.5h.01m11.99 0h.01");
}

</style>
