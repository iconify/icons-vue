<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_cb7ub1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bricklaying-trowel-sharp" /></template>
<style>
.q_cb7ub1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12L13 10.5l7.25 1.75h1v2h-1L13 15.75L4.25 14.5H3V12zm10.25-1.15l.75-4.1M7 3.75h9.25v3H7zm-4 14.5h18v3H3zm7 0v3");
}

</style>
