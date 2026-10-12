<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjvkfnb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:first-line-indent-sharp" /></template>
<style>
.fjvkfnb6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.5h16.5m-9 5h9m-9 5h9m-16.5 5h16.5M3.75 12h4.5m-2-2.5l2.5 2.5l-2.5 2.5");
}

</style>
