<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poh5-x5nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-autocomplete-sharp" /></template>
<style>
.poh5-x5nf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10h18.5v9.5H2.75zM6 14.75h4m1.75-2.5v5m2.25-2.5h1m1.75 0h1m1-12l.27 1.98L21 5l-1.98.27l-.27 1.98l-.27-1.98L16.5 5l1.98-.27z");
}

</style>
