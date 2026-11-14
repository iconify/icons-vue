<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="toa6e6kuk"/><path class="bwljf1bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:block-add" /></template>
<style>
.bwljf1bmn {
  d: path("m3.5 7.5l8.5 5l8.5-5m-8.5 5v9m6-6.5v6m-3-3h6");
}

.toa6e6kuk {
  d: path("M13.227 20.778L12 21.5l-8.5-5v-9l8.5-5l8.5 5v4.738");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
