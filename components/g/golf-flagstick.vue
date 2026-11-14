<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw6w_bcnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-flagstick" /></template>
<style>
.tw6w_bcnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 19.25a5.5 2.25 0 1 0 11 0a5.5 2.25 0 1 0-11 0ZM10.5 2.5v16.75m0-16.75l7.5 3l-7.5 3Z");
}

</style>
