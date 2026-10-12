<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qprfg-b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:decision-tree-ai-sharp" /></template>
<style>
.qprfg-b2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.57 3.32l2.61 2.61l.57.57l-.57.57l-2.61 2.61l-.57.57l-.57-.57l-2.61-2.61l-.57-.57l.57-.57l2.61-2.61l.57-.57zM12 10.25v2.25m-6 2.75V12.5h12v2.75m-15.25 0h6.5v6h-6.5zm12 0h6.5v6h-6.5z");
}

</style>
