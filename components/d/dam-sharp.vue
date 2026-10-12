<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imkr3ubwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dam-sharp" /></template>
<style>
.imkr3ubwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.59 20.5l1.82-15.75l.09-.75h3l.31.68l7.13 15.89l.31.68H8.5zm2.16-8H16M10.25 17H18M2.75 7.75c1.3 0 1.3-.75 2.6-.75s1.3.75 2.6.75m-5.2 4c1.3 0 1.3-.75 2.6-.75s1.3.75 2.6.75m-5.2 4c1.3 0 1.3-.75 2.6-.75s1.3.75 2.6.75");
}

</style>
