<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbqgvybyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deserialization" /></template>
<style>
.lbqgvybyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 4a1.25 1.25 0 0 0-1.25 1.25v5.25l-1 1.5l1 1.5v5.25A1.25 1.25 0 0 0 16.5 20m2.75-16a1.25 1.25 0 0 1 1.25 1.25v5.25l1 1.5l-1 1.5v5.25A1.25 1.25 0 0 1 19.25 20M2.5 4H6v3.5H2.5Zm0 6.25H6v3.5H2.5Zm0 6.25H6V20H2.5Zm6.5-7l2.5 2.5L9 14.5");
}

</style>
