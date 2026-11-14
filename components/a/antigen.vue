<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in7fpu08c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antigen" /></template>
<style>
.in7fpu08c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 12a5.75 5.75 0 1 0 11.5 0a5.75 5.75 0 1 0-11.5 0ZM12 6.25V3m-1.25 0h2.5M12 17.75V21m-1.25 0h2.5m-7-9H3m0-1.25v2.5M17.75 12H21m0-1.25v2.5M16 8l2.25-2.25m-1-1l2 2M8 8L5.75 5.75m-1 1l2-2M16 16l2.25 2.25m1-1l-2 2M8 16l-2.25 2.25m1 1l-2-2");
}

</style>
