<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsic8wbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crossfader-sharp" /></template>
<style>
.fsic8wbmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12H6.5m9 0h5.75M5.5 5.5V8m13-2.5V8m-13 8v2.5m13-2.5v2.5M8.25 7.75h5.5v8.5h-5.5zM11 10v4");
}

</style>
