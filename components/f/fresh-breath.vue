<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbk4u_8ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fresh-breath" /></template>
<style>
.rbk4u_8ur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20C3 12 7.5 5.5 15 4c1 7.5-3.5 14.5-11 16Zm0 0l6.5-10m6.25 2.5h4.75m-7.25 4h7.25m-12 4H18");
}

</style>
