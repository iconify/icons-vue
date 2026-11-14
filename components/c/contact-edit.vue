<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozakd4qlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contact-edit" /></template>
<style>
.ozakd4qlr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.2 21.5H4.5v-19H16v6.4m0 12.2v.4h-.4M2.75 6.5h3.5M2.75 12h3.5m-3.5 5.5h3.5M16 3.75h2.5v2.5H16m1.682 4.947l2.121 2.121l-6.717 6.718l-2.829.707l.707-2.829Z");
}

</style>
