<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-0bllbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:call-stack-sharp" /></template>
<style>
.h-0bllbem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75h13V7.5h-13zm0 7h13v4.5h-13zm0 6.75h13v4.75h-13zM4.5 20.75V4M2.75 5.75L4.5 4l1.75 1.75");
}

</style>
