<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgwrm0bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:land-plot-sharp" /></template>
<style>
.vgwrm0bjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.24 19.38l3.27-5.76l.49-.87h14.25l-.49.87l-3.27 5.76l-.49.87H2.75zM12 16.5V7.25m.56-4.28l4.63 1.81l.56.22l-.56.22l-4.63 1.81l-.56.22v-4.5z");
}

</style>
