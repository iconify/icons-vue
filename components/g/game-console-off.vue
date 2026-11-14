<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx87l3n6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:game-console-off" /></template>
<style>
.mx87l3n6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.9 6h11.6v11.6m-7.4.4H2.5V6.4m11 3.1h5m-13 3V15m3-2.5V15m-5-11.5l17 17");
}

</style>
