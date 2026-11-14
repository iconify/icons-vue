<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2vm05v_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biplane" /></template>
<style>
.f2vm05v_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 6.5l3 4h12a2 2 0 0 1 0 4h-15ZM7 6h10M9.5 6v4.5m5-4.5v4.5m-7 7H16m-4.25-3v3m7.75-5h2m0-4v8");
}

</style>
