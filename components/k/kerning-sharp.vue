<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7_zxnbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kerning-sharp" /></template>
<style>
.g7_zxnbev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 14.25L8 4.75l3.5 9.5M5.85 10.5h4.3m2.35-5.75l3.5 9.5l3.5-9.5M3.75 19h5.5m-2-2l2 2l-2 2m13-2h-5.5m2-2l-2 2l2 2");
}

</style>
