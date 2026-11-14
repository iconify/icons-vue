<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpsb-rbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barbed-wire" /></template>
<style>
.hpsb-rbtu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h19m-19 6h19m-15-7.5l3 3m0-3l-3 3m8-3l3 3m0-3l-3 3m-4 3l3 3m0-3l-3 3");
}

</style>
