<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gf_ffyb4u"/><path class="l6wh3u4fh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:buddhist-temple-sharp" /></template>
<style>
.gf_ffyb4u {
  d: path("m12.39 3.21l3.72 4.33l.39.46h2.75l.31.51l1.38 2.23l.31.51H2.75l.31-.51l1.38-2.23l.31-.51H7.5l.39-.46l3.72-4.33l.39-.46zM6 11.25h12v10H6z");
}

.l6wh3u4fh {
  d: path("M10.25 21.25v-5h3.5v5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
