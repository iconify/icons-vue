<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9bxccop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:benzene-ring-sharp" /></template>
<style>
.ba9bxccop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.3 3.5l5.41 3.13l1.3.75v9.25l-1.3.75l-5.41 3.12l-1.3.75l-1.3-.75l-5.41-3.12l-1.3-.75V7.38l1.3-.75L10.7 3.5l1.3-.75zm-.55 3.15l3.51 2.02m0 6.66l-3.51 2.02m-5.76-3.32V9.97");
}

</style>
