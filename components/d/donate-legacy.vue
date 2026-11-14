<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz03wbtkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:donate-legacy" /></template>
<style>
.tz03wbtkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h12m-12 17h9.7m-7.7-17L8.75 12L5.5 20.5m8-17L10.25 12l2 5.231m-5.5.019h5.4M18 21.5c-2-1.5-3-2.5-3-4.25C15 16 15.9 15 17 15c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c1.1 0 2 1 2 2.25C21 19 20 20 18 21.5Z");
}

</style>
