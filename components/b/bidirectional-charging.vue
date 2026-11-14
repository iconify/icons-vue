<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y262h88ci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bidirectional-charging" /></template>
<style>
.y262h88ci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6.5H19m-3-3l3 3l-3 3m4.5 8H5m3-3l-3 3l3 3m5-10.75l-2.5 2.5h3l-2.5 2.5");
}

</style>
