<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izscxhbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flash-compensation" /></template>
<style>
.izscxhbcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.619 11l.381-.5h-5.5l1-8L4 12h5.5L8 21l4.953-6.5m.969-1.273l1.273-1.67M15.75 16h4.5M18 13.75v4.5m-2.25 3h4.5");
}

</style>
