<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yolsw_s1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:door-open-warning-sharp" /></template>
<style>
.yolsw_s1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 2.75h9.5v18.5h-9.5zM9 7.25h6m-5.5 9.5h5M7.25 9l-4 3.75M16.75 9l4 3.75");
}

</style>
