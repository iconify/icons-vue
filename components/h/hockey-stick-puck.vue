<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oc736ybxq"/><path class="hd82dc2kw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hockey-stick-puck" /></template>
<style>
.hd82dc2kw {
  d: path("M14 16.75v2.5a3.5 1.5 0 0 0 7 0v-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oc736ybxq {
  d: path("m16 3.25l-7.5 13q-1.5 3-4.5 3h-.5a1.5 1.5 0 0 1-1.5-1.5m12-1a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0");
}

</style>
