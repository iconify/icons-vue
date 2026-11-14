<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-65j0bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-prescription" /></template>
<style>
.u-65j0bjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.575 14.475l9.9-9.9a1.5 1.5 0 0 1 2.121 0l2.829 2.829a1.5 1.5 0 0 1 0 2.121l-9.9 9.9a1.5 1.5 0 0 1-2.121 0l-2.829-2.829a1.5 1.5 0 0 1 0-2.121Zm4.95-4.95l4.95 4.95");
}

</style>
