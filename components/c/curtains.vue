<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt_yvbnma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:curtains" /></template>
<style>
.rt_yvbnma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19m-18 0v17h5C8.5 17 6 15 6 13c0-3 4.5-6 4.5-9.5m10 0v17h-5C15.5 17 18 15 18 13c0-3-4.5-6-4.5-9.5");
}

</style>
