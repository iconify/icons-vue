<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hv6h3wq6v"/><path class="fmhxclbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dwell-click" /></template>
<style>
.fmhxclbnm {
  d: path("M6 11.75a4.75 4.75 0 1 1 8.25-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv6h3wq6v {
  d: path("m10.11 8.84l9.53 5.32q.61.34-.07.51l-3.64.91q-.68.17-.96.81l-1.69 3.97q-.28.64-.47-.03L9.69 9.17q-.19-.67.42-.33");
}

</style>
