<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dm3_xlb0u"/><path class="e9_hoibmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-coat-person" /></template>
<style>
.dm3_xlb0u {
  d: path("M8.25 6.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM4 21.5V19c0-2.75 3-4.75 8-4.75s8 2 8 4.75v2.5");
}

.e9_hoibmi {
  d: path("m9 14.75l3 4.75l3-4.75m-3 4.75v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
