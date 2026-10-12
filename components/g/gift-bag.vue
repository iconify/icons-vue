<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc2egf_jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gift-bag" /></template>
<style>
.xc2egf_jg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.81 9.5L5.19 6q.06-.5.3-.06l2.02 3.62q.24.44-.26.44h-2q-.5 0-.44-.5m11.68.06l2.02-3.62q.24-.44.3.06l.38 3.5q.06.5-.44.5h-2q-.5 0-.26-.44M10 10V8a2 2 0 0 1 4 0v2m-7.75 0h11.5q1.25 0 1.36 1.25l.78 8.75q.11 1.25-1.14 1.25H5.25Q4 21.25 4.11 20l.78-8.75Q5 10 6.25 10");
}

</style>
