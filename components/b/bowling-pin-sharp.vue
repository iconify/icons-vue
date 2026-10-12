<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu0ac0b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bowling-pin-sharp" /></template>
<style>
.cu0ac0b8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c1.6 0 2.5 1.5 2.5 3.25c0 1.5-.9 2.5-.9 3.75c0 1.75 3.15 3.5 3.15 7.25v1.75l-1 2.5h-7.5l-1-2.5V17c0-3.75 3.15-5.5 3.15-7.25c0-1.25-.9-2.25-.9-3.75c0-1.75.9-3.25 2.5-3.25Zm-1.5 7h3");
}

</style>
