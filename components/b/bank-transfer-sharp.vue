<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ardt3zb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bank-transfer-sharp" /></template>
<style>
.ardt3zb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.52 8.61l4.21-3.47l.77-.64l.77.64l4.21 3.47l.77.64H2.75zM5 12v5m3.5-5v5m3.5-5v5m-9 2.75h11M16.25 12h5m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

</style>
