<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqlzaabzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:first-pass-yield" /></template>
<style>
.lqlzaabzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11.652 8.703q.17-.27.259-.577T15.25 13q0-.111-.011-.221t-.032-.218t-.054-.214t-.074-.208q-.043-.102-.095-.2q-.052-.097-.113-.189t-.132-.177q-.07-.086-.148-.164t-.164-.148t-.177-.132t-.189-.113t-.2-.095q-.102-.042-.208-.074t-.214-.054t-.218-.032T13 10.75t-.221.011t-.218.032q-.108.022-.214.054t-.208.074t-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164t-.132.177t-.113.189t-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221t.011.221t.032.218q.022.108.054.214t.074.208t.095.2q.052.097.113.189t.132.177q.07.086.148.164t.164.148t.177.132t.189.113t.2.095q.102.042.208.074t.214.054t.218.032t.221.011q.328 0 .642-.093M3 15.5L15.5 3m-.75 15l2 2L21 15.75");
}

</style>
