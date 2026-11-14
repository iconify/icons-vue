<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg08o0bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:display-light-spot" /></template>
<style>
.tg08o0bvs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19m-9.5 0v2.25m-2.5 0h5l1 4.75h-7ZM8.5 12l-4.25 7.5M15.5 12l4.25 7.5m-15.5 0a7.75 2 0 1 0 15.5 0a7.75 2 0 1 0-15.5 0Z");
}

</style>
