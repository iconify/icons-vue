<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev0in6nxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:covalent-bond" /></template>
<style>
.ev0in6nxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm12 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-2-1.5h.01m-.01 3h.01M6 12h.01M18 12h.01");
}

</style>
