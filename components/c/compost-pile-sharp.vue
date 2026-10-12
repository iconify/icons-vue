<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnpd4jbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compost-pile-sharp" /></template>
<style>
.gnpd4jbbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.28 20.4L9.97 9.6l.53-.85l.53.85l6.69 10.8l.53.85H2.75zm4.47-4.9h5.5M5.5 18.75h10m-1.25-6.25L19 4.75m-1-1l2.25 1.5");
}

</style>
