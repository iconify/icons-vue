<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcn4ksbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:greenhouse-humidity" /></template>
<style>
.rcn4ksbem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.723 19.5H2.5V10L11 3l8.5 7v1.077M2.5 10h17M6 10v9.5M16 10v2.6m2.5 1.4s-3 3-3 4.75a3 3 0 0 0 6 0c0-1.75-3-4.75-3-4.75Z");
}

</style>
