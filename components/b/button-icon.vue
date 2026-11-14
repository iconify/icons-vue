<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmqgagsie"/><path class="pbst-vgix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:button-icon" /></template>
<style>
.hmqgagsie {
  d: path("M10 3h4a7 7 0 0 1 7 7v4a7 7 0 0 1-7 7h-4a7 7 0 0 1-7-7v-4a7 7 0 0 1 7-7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbst-vgix {
  d: path("m12.735 8.489l.382.905a1.5 1.5 0 0 0 1.254.911l.979.084a.798.798 0 0 1 .454 1.397l-.743.644a1.5 1.5 0 0 0-.478 1.474l.222.957a.798.798 0 0 1-1.189.864l-.841-.508a1.5 1.5 0 0 0-1.55 0l-.841.508a.798.798 0 0 1-1.189-.864l.222-.957a1.5 1.5 0 0 0-.478-1.474l-.743-.644a.798.798 0 0 1 .454-1.397l.979-.084a1.5 1.5 0 0 0 1.254-.911l.382-.905a.798.798 0 0 1 1.47 0");
}

</style>
