<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9y5p2b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:installments" /></template>
<style>
.y9y5p2b4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.37 13.48a8.5 8.5 0 0 1-6.89 6.89m-2.96 0a8.5 8.5 0 0 1-6.89-6.89m0-2.96a8.5 8.5 0 0 1 6.89-6.89m2.96 0a8.5 8.5 0 0 1 6.89 6.89m-6.62-.77c-.4-.6-1-.9-1.75-.9c-1.1 0-1.9.6-1.9 1.5c0 2 3.75 1.25 3.75 3.25c0 .9-.85 1.55-1.95 1.55c-.8 0-1.45-.35-1.85-1M12 7.5v1.35m0 6.3v1.35");
}

</style>
