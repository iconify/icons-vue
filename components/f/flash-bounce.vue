<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhjrjt61e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flash-bounce" /></template>
<style>
.uhjrjt61e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19M5 17l3-5l4 4l-5 3Zm1 1l-2.5 2.5M11 11l5.5-5.5l4 4m-2.75 0h2.75V6.75");
}

</style>
