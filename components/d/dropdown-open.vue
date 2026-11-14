<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vzjd6hbbu"/><path class="bphvhnb4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dropdown-open" /></template>
<style>
.bphvhnb4p {
  d: path("m12.75 13.5l3-3l3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vzjd6hbbu {
  d: path("M2.5 6h19v12h-19Zm3 6h4.25");
}

</style>
