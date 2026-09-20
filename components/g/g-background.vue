<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="o4mw8mjso"/><path class="zomzc88sk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:g-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o4mw8mjso {
  fill: var(--svg-color--ffac43, #ffac43);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.zomzc88sk {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.945 7.424a.41.41 0 0 0-.567-.145l-10.53 6.407a3.581 3.581 0 0 1 5.402-4.477l-2.24 1.538l5.821-3.363a.262.262 0 1 0-.28-.443l-1.425.979a5.78 5.78 0 0 0-4.118-1.72a5.798 5.798 0 0 0-5.056 8.64L4 16.634l3.031-1.66a5.79 5.79 0 0 0 4.977 2.825a5.8 5.8 0 0 0 5.796-5.8v-.693c0-.542.22-1.236 1-1.654a.134.134 0 1 0-.13-.235l-6.912 3.993c.772-.328 1.361-.527 2.143-.684c1.629-.328 1.67.45 1.041 1.326c-.42.586-1.372 1.529-2.937 1.529a3.58 3.58 0 0 1-3.03-1.674l10.808-5.92a.41.41 0 0 0 .158-.564");
}

</style>
