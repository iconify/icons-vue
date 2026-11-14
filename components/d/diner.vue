<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qwkzdyb0f"/><path class="qxw_ngjkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diner" /></template>
<style>
.qwkzdyb0f {
  d: path("m4 10.5l8-7l8 7v10H4Z");
}

.qxw_ngjkf {
  d: path("M16 7V4h2v4.75M8.5 12.5h6V15a2.5 2.5 0 0 1-2.5 2.5h-1A2.5 2.5 0 0 1 8.5 15Zm6 .5h.5a1.75 1.75 0 0 1 0 3.5h-.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
