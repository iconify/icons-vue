<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raporibtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checkout-lane" /></template>
<style>
.raporibtk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5h19V20h-19Zm.5-11h6.5v5H3Zm3.25 5v6m6.75-6h6v6h-6Zm-6 8.75h.01m4.99 0h.01m4.99 0h.01");
}

</style>
