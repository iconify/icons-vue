<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrs0yaccl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-pit" /></template>
<style>
.qrs0yaccl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14.5h18c0 3.75-4 6-9 6s-9-2.25-9-6Zm9-2c-2.75 0-4-1.75-4-3.75C8 6.25 10.25 5 10.75 2.5C12.25 3.75 13 5.25 13 6.75c.75-.75 1.25-1.5 1.5-2.5c1.25 1.5 1.5 3 1.5 4.5c0 2-1.25 3.75-4 3.75Z");
}

</style>
