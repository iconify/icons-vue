<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnxn52b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chorus-effect" /></template>
<style>
.hnxn52b8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0V13m3 2.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0V9m3 2.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0V3");
}

</style>
