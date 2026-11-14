<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d18wj5b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antenna-receive" /></template>
<style>
.d18wj5b-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 9.5v11m-2.5 0H13M9.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-3.479 4.178a6.5 6.5 0 0 1 0-8.356m9.958 0q.171.204.325.421t.289.446t.252.468t.213.488t.172.503t.131.515q.054.261.088.525t.044.53q.012.265.002.531t-.042.53q-.032.265-.086.525q-.053.261-.128.516q-.074.256-.169.504q-.095.249-.211.489t-.249.469q-.134.23-.287.448M18 14.5v7m-3-3l3 3l3-3");
}

</style>
