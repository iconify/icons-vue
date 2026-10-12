<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnwnt3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:finish-flag-sharp" /></template>
<style>
.qnwnt3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75v18.5m18.5-18.5v18.5m-18.5-17h18.5v4H2.75zm6 0v4m6.5-4v4M2.75 13.5H11l1 1.5l1-1.5h8.25");
}

</style>
