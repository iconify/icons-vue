<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxgu6jbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:express-lane" /></template>
<style>
.cxgu6jbml {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.08 20.5H4.5l-2-11h19l-.429 2.361M7 9.5l3-6m7 6l-3-6m-6.5 9v5m4-5v5m7.5-3.75l-3.75 4.75l5-.5l-3.5 4");
}

</style>
