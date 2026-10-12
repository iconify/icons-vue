<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9o19obtj"/><circle class="n4tbcbbac"/><circle class="yssow-b-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emissions-stack" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4tbcbbac {
  cx: 11px;
  cy: 5.25px;
  r: 2.5px;
}

.s9o19obtj {
  d: path("m5.1 20.51l1.3-9.77q.1-.74.85-.74h2.5q.75 0 .85.74l1.3 9.77q.1.74-.65.74h-5.5q-.75 0-.65-.74M6.25 14h4.5");
}

.yssow-b-l {
  cx: 18.5px;
  cy: 5px;
  r: 2px;
}

</style>
