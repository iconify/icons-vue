<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx9p6bc-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artist-profile-plus" /></template>
<style>
.yx9p6bc-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM3 21.5c0-4.5 3-7.25 7-7.25q2.25 0 3.75.75M18 15v6m-3-3h6");
}

</style>
