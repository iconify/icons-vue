<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oisd6i2lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:city-gate-arch" /></template>
<style>
.oisd6i2lf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21V4H8v5h8V4h5.5v17h-7.25v-5.5a2.25 2.25 0 0 0-4.5 0V21ZM5.25 8.5v3m13.5-3v3");
}

</style>
