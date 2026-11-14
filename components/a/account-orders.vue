<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axe7b2bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-orders" /></template>
<style>
.axe7b2bep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13h15v8.5h-15Zm3 0V4.5a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2V13m-12 0L2.25 9.5M19.5 13l2.25-3.5m-11.5-3.25h.01m1.74 0h2m-3.75 3.5h.01m1.74 0h2");
}

</style>
