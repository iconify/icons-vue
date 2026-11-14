<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahfclccna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:function-cold-start" /></template>
<style>
.ahfclccna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5q-4 8 0 16m8-16q3.201 6.403 1.278 12.806M11.75 5.5A2.25 2.25 0 0 0 9.5 7.75v7.75m-2-5.5h4m7.5 6.25v5.5m2.382-4.125l-4.764 2.75m4.764 0l-4.764-2.75");
}

</style>
