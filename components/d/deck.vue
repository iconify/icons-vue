<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="um711ubdc"/><path class="s03df9b0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deck" /></template>
<style>
.s03df9b0k {
  d: path("M4.5 12.75v8.75m9-8.75v8.75M2.5 5h13m0 7.75H18V17h3.5v4.5m-19 0h19M6 5v6m3-6v6m3-6v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.um711ubdc {
  fill: currentColor;
  d: path("M2.5 11h13v1.75h-13Z");
}

</style>
