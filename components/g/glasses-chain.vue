<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7u_8umir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glasses-chain" /></template>
<style>
.p7u_8umir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5h7.25v2.75c0 2-1.25 3.25-3.25 3.25h-.75C4.25 10.5 3 9.25 3 7.25Zm18 0h-7.25v2.75c0 2 1.25 3.25 3.25 3.25h.75c2 0 3.25-1.25 3.25-3.25ZM10.25 5.75C11 5 13 5 13.75 5.75M3.25 13.5h.01m1.49 2.75h.01m2.24 2h.01m2.49 1h.01m2.49.25h.01m2.49-.25h.01m2.49-1h.01m2.24-2h.01m1.49-2.75h.01");
}

</style>
