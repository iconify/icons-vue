<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hzqyndvup"/><path class="ma_0rxbbq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boiler" /></template>
<style>
.hzqyndvup {
  d: path("M5 2.5h14v15H5Zm4 3h6");
}

.ma_0rxbbq {
  d: path("M12 15c-1.75 0-2.75-1.25-2.75-2.75C9.25 10.5 10.75 9.5 11 8c1 .75 1.5 1.5 1.5 2.5c.5-.5.75-1 1-1.75c.75 1 1.25 2.25 1.25 3.5c0 1.5-1 2.75-2.75 2.75Zm-3 2.5v4m6-4v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
