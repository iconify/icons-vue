<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k16w-5bpc"/><path class="i_hfzxbzl"/><circle class="ptricrbgn"/><path class="wf96h2k6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:decrypt-key" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_hfzxbzl {
  d: path("M6.5 6.5h11m-11 3h7");
}

.k16w-5bpc {
  width: 18.5px;
  height: 9.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.ptricrbgn {
  cx: 6px;
  cy: 17.75px;
  r: 3.25px;
}

.wf96h2k6o {
  d: path("M9.25 17.75h11.5m-2.25 0v2.5m-2.75-2.5v1.75");
}

</style>
