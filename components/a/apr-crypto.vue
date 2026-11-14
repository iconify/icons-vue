<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1_scub4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apr-crypto" /></template>
<style>
.u1_scub4i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5h11.5a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H8l-5.5-7Zm2.5 10.5l6-7m-5.75.5h.01m5.49 6h.01");
}

</style>
