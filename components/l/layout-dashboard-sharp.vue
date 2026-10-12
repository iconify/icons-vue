<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odmcbjkxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:layout-dashboard-sharp" /></template>
<style>
.odmcbjkxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h7.5v9.5h-7.5zm10.5 0h8v6h-8zm-10.5 12.5h7.5v6h-7.5zm10.5-3.5h8v9.5h-8z");
}

</style>
