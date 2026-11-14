<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f53rllbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flask-empty" /></template>
<style>
.f53rllbdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3v6.5l-5 9.75A1.5 1.5 0 0 0 5.75 21h12.5a1.5 1.5 0 0 0 1.25-1.75l-5-9.75V3M8 3h8");
}

</style>
