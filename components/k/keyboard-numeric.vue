<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdigtqb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keyboard-numeric" /></template>
<style>
.fdigtqb-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14v19H5Zm4 4h.01m2.99 0h.01m2.99 0h.01M9 10h.01M12 10h.01M15 10h.01M9 13.5h.01m2.99 0h.01m2.99 0h.01M9 17.5h3m3 0h.01");
}

</style>
