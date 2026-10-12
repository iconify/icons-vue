<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy-9opbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:installments-sharp" /></template>
<style>
.hy-9opbbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.37 13.48a8.5 8.5 0 0 1-6.89 6.89m-2.96 0a8.5 8.5 0 0 1-6.89-6.89m0-2.96a8.5 8.5 0 0 1 6.89-6.89m2.96 0a8.5 8.5 0 0 1 6.89 6.89m-6.62-.77l-.6-.9H10.1v1.5c0 2 3.75 1.25 3.75 3.25v1.55h-3.185l-.615-1M12 7.5v1.35m0 6.3v1.35");
}

</style>
