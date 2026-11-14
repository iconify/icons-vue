<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxegkccfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cart-scanner-handle" /></template>
<style>
.bxegkccfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 4.5H20.5l-1.75 7H7Zm-2.75-2h2l2.5 9m-1.5 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.442-1.392q-.104.041-.2.098q-.097.056-.184.126t-.162.153t-.138.175t-.111.193t-.081.207t-.049.218q-.017.11-.017.222q0 .113.017.224q.017.112.05.219q.033.108.082.21q.05.101.113.194q.064.093.141.176t.165.152t.186.127q.098.056.203.096M14.75 15h6.75v3H19l-.75 3.5H16l.75-3.5h-2Z");
}

</style>
