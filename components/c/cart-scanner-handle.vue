<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mahf9jkrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cart-scanner-handle" /></template>
<style>
.mahf9jkrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.491 4.5h10.768a1.75 1.75 0 0 1 1.697 2.174l-.875 3.5a1.75 1.75 0 0 1-1.697 1.326H8.366a1.75 1.75 0 0 1-1.697-1.326l-.875-3.5A1.75 1.75 0 0 1 7.491 4.5M2.5 2.5h2l2.5 9m-1.5 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6.442-1.392q-.104.041-.2.098q-.097.056-.184.126t-.162.153t-.138.175t-.111.193t-.081.207t-.049.218q-.017.11-.017.222q0 .113.017.224q.017.112.05.219q.033.108.082.21q.05.101.113.194q.064.093.141.176t.165.152t.186.127q.098.056.203.096M14.75 15h6.75v3H19l-.75 3.5H16l.75-3.5h-2Z");
}

</style>
