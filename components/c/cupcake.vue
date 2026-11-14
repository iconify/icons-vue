<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zios_kbih"/><path class="tkc4f71og"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cupcake" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tkc4f71og {
  d: path("M4.75 12.5c-1 0-1.5-.75-1.25-1.75C4.25 7.25 7.75 5 12 5s7.75 2.25 8.5 5.75c.25 1-.25 1.75-1.25 1.75Zm5.25 0l.5 8m3.5-8l-.5 8M12 2.5h.01");
}

.zios_kbih {
  d: path("M7.753 12.5h8.494a1.5 1.5 0 0 1 1.482 1.732l-.781 5a1.5 1.5 0 0 1-1.482 1.268H8.534a1.5 1.5 0 0 1-1.482-1.268l-.781-5A1.5 1.5 0 0 1 7.753 12.5");
}

</style>
