<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bflixzf2l"/><rect class="udf2ji8xe"/><rect class="kyjhm5bmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ink-pad" /></template>
<style>
.bflixzf2l {
  d: path("m4.22 10.12l1.31-2.49Q6 6.75 7 6.75h10q1 0 1.47.88l1.31 2.49q.47.88-.53.88H4.75q-1 0-.53-.88");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kyjhm5bmg {
  width: 13.5px;
  height: 2.75px;
  x: 5.25px;
  y: 16px;
  rx: 1px;
}

.udf2ji8xe {
  width: 18.5px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 2px;
}

</style>
