<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y8sm46qhb"/><path class="fwgc4z0nd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheque-blank" /></template>
<style>
.fwgc4z0nd {
  d: path("M13.75 7.75h5V11h-5ZM5.5 15.5h1.25m5.75 0h1.25m2.75 0h1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y8sm46qhb {
  d: path("M2.5 5h19v14h-19Zm3 4.5h1.25m2.75 0h1.25");
}

</style>
