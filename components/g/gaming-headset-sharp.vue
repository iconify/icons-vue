<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxe8e0pqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gaming-headset-sharp" /></template>
<style>
.dxe8e0pqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12v-.75a7.5 7.5 0 0 1 15 0V12M2.75 12h5v8h-5zm13.5 0h5v8h-5zm-11 2.75v3m13.5-3v3m-11 .25L10 21h4");
}

</style>
