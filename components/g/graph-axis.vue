<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jkapk7bva"/><path class="v8tdnrbxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:graph-axis" /></template>
<style>
.jkapk7bva {
  d: path("M4.5 3v16.5H21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8tdnrbxp {
  d: path("m2.5 5l2-2l2 2M19 17.5l2 2l-2 2m-9.5-2V17m5 2.5V17");
}

</style>
