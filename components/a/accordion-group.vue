<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vwp645bdx"/><path class="f6w5fk61k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accordion-group" /></template>
<style>
.f6w5fk61k {
  d: path("m16 3.75l1 1l1-1M7 11.5h7M7 14h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vwp645bdx {
  d: path("M4 2.5h16v3.75H4ZM4 9h16v7.5H4Zm0 10.25h16v2.25H4Z");
}

</style>
