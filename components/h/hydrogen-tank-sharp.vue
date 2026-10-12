<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0ae57bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hydrogen-tank-sharp" /></template>
<style>
.g0ae57bou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6h11v15.25h-11zm3.25-3.25h4.5m-2.25 0V6m-2 4.75v6m4-6v6m-4-3h4");
}

</style>
