<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6mmmtb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bridge-road-sharp" /></template>
<style>
.v6mmmtb2m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25h18.5v2.5H2.75zM5 18a9 9 0 0 1 14 0M5 11.75V18m14-6.25V18M9 11.75v3.4m3-3.4v2.9m3-2.9v3.4M7.5 20.5l1-1l1 1l1 1l1-1m1 0l1-1l1 1l1 1l1-1");
}

</style>
