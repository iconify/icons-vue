<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdb9_1bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:handshake-plus" /></template>
<style>
.qdb9_1bso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5H6v7H2.5m19-7H18v7h3.5M6 6l4.5-2h3L18 6v4.5l-4.5 3a1.5 1.5 0 0 1-2-1L6 10Zm4 1.75L13.5 10m4.5 5v6m-3-3h6");
}

</style>
