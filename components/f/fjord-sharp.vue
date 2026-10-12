<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frfgwijxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fjord-sharp" /></template>
<style>
.frfgwijxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.35V4l.86-.26l1.53-.48L6 3l.55.71L9.7 7.79l.55.71l-.25.86l-3.25 11.03l-.25.86H2.75zm18.5 0V6l-.86-.26l-1.53-.48L18 5l-.69.57l-2.87 2.36l-.69.57l.25.86l3.25 11.03l.25.86h3.75zm-11-1.6l.875-.754l.875.754l.875.754l.875-.754m-2.75-4l.5-.606l.5.606l.5.606l.5-.606");
}

</style>
