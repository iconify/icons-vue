<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xikokabpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:business-trip-sharp" /></template>
<style>
.xikokabpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11h12.5v10.25H2.75zM7 11V8.25h4V11m-8.25 4.5h12.5m3-12.75v7m-3-2.75l3-1.5l3 1.5M17 9.75h2.5");
}

</style>
