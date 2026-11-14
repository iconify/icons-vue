<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ljj4pabep"/><path class="trn1rwa5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-health-delivery" /></template>
<style>
.ljj4pabep {
  d: path("M11.4 19H2.5V6h15v5.2M10 6v5M2.5 9.5h15M14.25 18L18 14.5l3.75 3.5");
}

.trn1rwa5g {
  d: path("M15.5 17v4.5h5V17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
