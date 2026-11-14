<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od3_-dhfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ceramic-bowl" /></template>
<style>
.od3_-dhfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5h15c0 4.5-3 7-6 7h-3c-3 0-6-2.5-6-7Zm-2 7h19v3h-19Zm9.5 3v4.5m-4.5 0h9");
}

</style>
