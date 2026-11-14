<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdtl5cb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:active-threat" /></template>
<style>
.vdtl5cb0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l7.5 2.75V11c0 5-3.25 8.5-7.5 10.5c-4.25-2-7.5-5.5-7.5-10.5V5.25ZM12 7v5.25m0 3.5h.01");
}

</style>
