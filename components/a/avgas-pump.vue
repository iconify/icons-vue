<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eor4h2b3c"/><path class="pies4u9yp"/><path class="nf-85y0pi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avgas-pump" /></template>
<style>
.eor4h2b3c {
  d: path("M13 18.4v3.1H3V3h10v12.1");
}

.nf-85y0pi {
  d: path("M17.5 18.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.pies4u9yp {
  d: path("M5.75 5.75h4.5v3.5h-4.5ZM13 6.5h2A2.5 2.5 0 0 1 17.5 9v3m-2 4.75a1.25 1.75 0 1 0 2.5 0a1.25 1.75 0 1 0-2.5 0Zm3.5 3.5a1.25 1.75 0 1 0 2.5 0a1.25 1.75 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
