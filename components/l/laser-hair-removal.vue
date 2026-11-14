<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1fv24kyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:laser-hair-removal" /></template>
<style>
.b1fv24kyt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.121 10.343l3.536 3.536l-7.778 7.778l-3.536-3.536ZM14 10l5-5m-7.25 2.75l5-5m-.5 9.5l5-5");
}

</style>
