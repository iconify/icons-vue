<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1k26je4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heater-sharp" /></template>
<style>
.b1k26je4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75v1.5m4-1.5v1.5m4-1.5v1.5M2.75 6.75h18.5v12H2.75zm4.75 3v6m4.5-6v6m4.5-6v6m-10.5 3v2.5m12-2.5v2.5");
}

</style>
