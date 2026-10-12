<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8ovv9mhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corner-sofa-sharp" /></template>
<style>
.a8ovv9mhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.5v-6h14.5v6m-16.5 2v-2h4v3.25h10.5V10.5h4v9.25H2.75v-2Zm2.5 7.25v1.5m13.5-1.5v1.5");
}

</style>
