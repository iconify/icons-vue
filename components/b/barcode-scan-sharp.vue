<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klgfk4b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barcode-scan-sharp" /></template>
<style>
.klgfk4b3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 8V3.25H8m8 0h4.75V8m0 8v4.75H16m-8 0H3.25V16m4.5-8.25v8.5m3-8.5v8.5m2.5-8.5v8.5m3-8.5v8.5M5.25 12h13.5");
}

</style>
