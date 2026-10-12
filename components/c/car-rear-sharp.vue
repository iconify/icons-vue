<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml3g0pb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-rear-sharp" /></template>
<style>
.ml3g0pb3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17v-4.75l1-.5l1-.5l.41-1.18l1.18-3.39l.41-1.18h10.5l.41 1.18l1.18 3.39l.41 1.18l1 .5l1 .5v6H2.75zm3.5 1.25v2.5m11.5-2.5v2.5m-3-2.5v1.25m-9.25-9h13m-8.25 5h3.5M5.25 14h2.5m8.5 0h2.5");
}

</style>
