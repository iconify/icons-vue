<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6tcf3r8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-contactless" /></template>
<style>
.r6tcf3r8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.7 17.5H2.5V3h15v6.7M2.5 8h15M10 3v5m4.5 13.75V15.5a1.25 1.25 0 0 1 2.5 0v-1.75a1.25 1.25 0 0 1 2.5 0v1.75a1.25 1.25 0 0 1 2.5 0v3.25a3 3 0 0 1-3 3Z");
}

</style>
