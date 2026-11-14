<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amh1sabfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-mirror" /></template>
<style>
.amh1sabfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14q4.5 4.5 11 3.5m0-2h8v4h-8Zm-7.5 1v5m11-6l-.25-4M12 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

</style>
