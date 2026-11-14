<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myx7qnt-b"/><path class="pp1gyvbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:incidental-charges" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.myx7qnt-b {
  d: path("M17.25 7h2.5a1 1 0 0 1 1 1v13.5l-2-1.5l-2 1.5l-2-1.5l-2 1.5l-2-1.5v-6.5");
}

.pp1gyvbwr {
  d: path("M6.75 4h7a3.5 3.5 0 0 1 3.5 3.5V10a3.5 3.5 0 0 1-3.5 3.5h-7a3.5 3.5 0 0 1-3.5-3.5V7.5A3.5 3.5 0 0 1 6.75 4m7 12.75h4M3.25 7.5h14");
}

</style>
