<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2i7k4bss"/><path class="tiitzedzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:failover" /></template>
<style>
.d2i7k4bss {
  d: path("M2.5 4.5H10c4 0 5 3.5 5 11m1.5-11h5M2.5 19h19");
}

.tiitzedzb {
  d: path("M12.75 13.25L15 15.5l2.25-2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
