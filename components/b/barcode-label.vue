<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoyiqmblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barcode-label" /></template>
<style>
.uoyiqmblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.75h14.5a2 2 0 0 1 2 2v10.5a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2V6.75a2 2 0 0 1 2-2m1.5 3v6.5m2.25-6.5v6.5m2.5-6.5v6.5m2.25-6.5v6.5m2.25-6.5v6.5m2.25-6.5v6.5m-9.25 2.5h7");
}

</style>
