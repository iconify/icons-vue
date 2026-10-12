<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe4a5x52e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:call-waiting-sharp" /></template>
<style>
.fe4a5x52e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.6 3.25h2.6l.72-.002l.23.682l1.1 3.3l.19.587l-.44.433l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6l.433-.44l.587.19l3.3 1.1l.682.23l-.002.72v4.95H18.4c-8.3 0-15.15-6.85-15.15-15.15V3.25zm9.9-.5h5m-5 7.5h5m-4.25-7.5v2.523L17.3 6l.7.5l.7.5l1.05.727v2.523m0-7.5v2.523L18.7 6l-.7.5l-.7.5l-1.05.727v2.523");
}

</style>
