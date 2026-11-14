<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ddty55nuu"/><path class="m9r7aqb6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chicken-run" /></template>
<style>
.ddty55nuu {
  d: path("m3.396 9.517l2.75-3.362a1.75 1.75 0 0 1 2.708 0l2.75 3.362A1.75 1.75 0 0 1 12 10.625v7.625A1.75 1.75 0 0 1 10.25 20h-5.5A1.75 1.75 0 0 1 3 18.25v-7.625a1.75 1.75 0 0 1 .396-1.108M12 12.5h9m-9 4h9m-4.5-7V20M21 9.5V20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9r7aqb6z {
  d: path("M6 20v-2.5a1.5 1.5 0 0 1 3 0V20");
}

</style>
