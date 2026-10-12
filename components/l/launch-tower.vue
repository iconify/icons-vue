<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l00x1dhwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:launch-tower" /></template>
<style>
.l00x1dhwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.25V2.75H8v18.5m-4.5-15l4.5 3l-4.5 3l4.5 3l-4.5 3M8 7.5h4.25m4-4.75c1.9 1.5 3 3.6 3 6.25v10h-6V9c0-2.65 1.1-4.75 3-6.25m-13.5 18.5h18.5");
}

</style>
