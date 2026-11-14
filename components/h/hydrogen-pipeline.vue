<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb1p_63qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hydrogen-pipeline" /></template>
<style>
.xb1p_63qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14H15V9.5h4.5V16a2.5 2.5 0 0 1-2.5 2.5H2.5Zm14.75-9.5v5m-3.75-5H21");
}

</style>
