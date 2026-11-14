<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzp7uy9kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-break" /></template>
<style>
.pzp7uy9kp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.2 17.5H2.5v-11h17v6.2M8.5 2.5l2.5 4l2.5-4m-2.5 15v3m-2.5 0h4.7M16 17h1.5l4-2.25v6.75l-4-2.25H16Z");
}

</style>
