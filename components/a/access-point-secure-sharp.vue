<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5t-94xsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:access-point-secure-sharp" /></template>
<style>
.l5t-94xsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.92 7.25a12 12 0 0 1 18.16 0M7 9.5a7.5 7.5 0 0 1 10 0M5 21.25h14m-10-7.5h6v5H9zm1 0V10.5h4v3.25");
}

</style>
