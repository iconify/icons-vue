<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="hju17kbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:insurance-claim" /></template>
<style>
.eoz3zibrm {
  d: path("M4.5 2.5h15v19h-15Z");
}

.hju17kbjq {
  d: path("M8 9c0-2.25 1.75-3.75 4-3.75s4 1.5 4 3.75Zm4 0v1.5m-4 3.25h8m-8 3.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
