<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n7fh31b2x"/><path class="imh7vgi-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:church-spire" /></template>
<style>
.imh7vgi-c {
  d: path("M10.5 21v-4.5h3V21");
}

.n7fh31b2x {
  d: path("M6 21v-9h12v9M8 12l4-7.5l4 7.5m-4-7.5v-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
