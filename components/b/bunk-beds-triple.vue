<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2k3pccsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bunk-beds-triple" /></template>
<style>
.x2k3pccsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5v19m17-19v19M3.5 8h17m-17 5.5h17M3.5 19h17M6.5 8V6h3v2m-3 5.5v-2h3v2m-3 5.5v-2h3v2");
}

</style>
