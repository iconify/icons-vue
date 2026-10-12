<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nky4ouekq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:amphitheater-sharp" /></template>
<style>
.nky4ouekq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.5a9.25 9.25 0 0 0 18.5 0m-15.5 0a6.25 6.25 0 0 0 12.5 0m-9.5 0a3.25 3.25 0 0 0 6.5 0M5.5 18.75h13");
}

</style>
