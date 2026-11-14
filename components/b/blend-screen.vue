<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kebju1mox"/><path class="f7bkafbnj"/><path class="uuo_wzbik"/><path class="nvupkhb5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blend-screen" /></template>
<style>
.f7bkafbnj {
  d: path("M9 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kebju1mox {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3");
}

.nvupkhb5v {
  d: path("M11.25 13.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.uuo_wzbik {
  d: path("M6.75 13.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
