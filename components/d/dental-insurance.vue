<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n_fijn9jq"/><path class="dls30wbxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-insurance" /></template>
<style>
.dls30wbxc {
  d: path("M7.25 6.75c-1.5 0-2 1-2 2.5s.75 2.5 1 3.75l.25 1.25c.25.75 1 .75 1.25 0l.5-1.75h1l.5 1.75c.25.75 1 .75 1.25 0l.25-1.25c.25-1.25 1-2.25 1-3.75s-.5-2.5-2-2.5c-.75 0-1 .5-1.5.5s-.75-.5-1.5-.5ZM14.75 18l2 2L21 15.75");
}

.n_fijn9jq {
  d: path("M10.8 18H2.5V4h19v8.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
