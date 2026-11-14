<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="promi4brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-server" /></template>
<style>
.promi4brw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 13h11a3.25 3.25 0 0 0 0-6.5A5.5 5.5 0 0 0 7 7a3 3 0 0 0-.5 6Zm5.5 0v2.75m-9 0h18v5.5H3Zm3.75 2.75h.01m5.74 0h5");
}

</style>
