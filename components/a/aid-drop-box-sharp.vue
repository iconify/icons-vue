<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0w9txvxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:aid-drop-box-sharp" /></template>
<style>
.w0w9txvxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.25a8.25 6.25 0 0 1 16.5 0Zm.75 0l3.75 4m11.25-4l-3.75 4m-8.25 0h9v8h-9zm4.5 2.5v3.5m-1.75-1.75h3.5");
}

</style>
