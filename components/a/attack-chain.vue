<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g5ogw-q3r"/><path class="ygy1rpboz"/><path class="rwqqhuvec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:attack-chain" /></template>
<style>
.g5ogw-q3r {
  d: path("m2.404 18.414l6.01-6.01l3.182 3.182l-6.01 6.01Z");
}

.rwqqhuvec {
  d: path("m12.404 8.414l6.01-6.01l3.182 3.182l-6.01 6.01Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygy1rpboz {
  d: path("m7.404 13.414l6.01-6.01l3.182 3.182l-6.01 6.01Z");
}

</style>
