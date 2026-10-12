<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p7wzmmb7f"/><path class="i5vfp64-a"/><rect class="r3xibbctd"/><rect class="zmf1mqbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flowchart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i5vfp64-a {
  d: path("M8.5 6.5v2.75m0 5.5v2.75m2.75-5.5h4.5M9.03 9.78l1.69 1.69q.53.53 0 1.06l-1.69 1.69q-.53.53-1.06 0l-1.69-1.69q-.53-.53 0-1.06l1.69-1.69q.53-.53 1.06 0");
}

.p7wzmmb7f {
  width: 9px;
  height: 3.75px;
  x: 4px;
  y: 2.75px;
  rx: 1.25px;
}

.r3xibbctd {
  width: 9px;
  height: 3.75px;
  x: 4px;
  y: 17.5px;
  rx: 1.25px;
}

.zmf1mqbkx {
  width: 5.5px;
  height: 4.5px;
  x: 15.75px;
  y: 9.75px;
  rx: 1.25px;
}

</style>
