<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="saogqm4vu"/><path class="y6h75vxkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-format" /></template>
<style>
.saogqm4vu {
  d: path("M12.2 19H3V2.5h13v10.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6h75vxkq {
  d: path("m8 8l-2 2.5L8 13m3-5l2 2.5l-2 2.5m4 2.5h6m-3.5 3H21m-6 3h6");
}

</style>
