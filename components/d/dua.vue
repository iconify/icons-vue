<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lcswgybdj"/><path class="f5ukw-b-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dua" /></template>
<style>
.f5ukw-b-k {
  fill: var(--svg-color--86d900, #86d900);
  d: path("M4.692 6.938A1.687 1.687 0 0 1 6.379 5.25h7.875a3.375 3.375 0 1 1 0 6.75a3.375 3.375 0 1 1-3.375 3.375v.281a3.094 3.094 0 0 1-6.187 0z");
}

.ft5dv1b6b {
  fill: none;
}

.lcswgybdj {
  fill: var(--svg-color--1e1e1e, #1e1e1e);
  d: path("M5.35 3a2.346 2.346 0 0 0-2.346 2.346v13.308A2.35 2.35 0 0 0 5.35 21h11.154a4.5 4.5 0 0 0 .664-8.95A4.555 4.555 0 0 0 16.454 3z");
}

</style>
