<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnz1n3mlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-tower-lattice" /></template>
<style>
.bnz1n3mlv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 21l3-13.5h5l3 13.5M8 14.25h8M10.75 3h2.5v4.5h-2.5ZM8 14.25L17.5 21M16 14.25L6.5 21");
}

</style>
