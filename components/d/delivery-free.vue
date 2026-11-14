<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b4jlwyb2r"/><path class="urldrljgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-free" /></template>
<style>
.b4jlwyb2r {
  d: path("m12.47 17.387l-1.625.897q-.194.107-.409.162t-.436.056t-.436-.056q-.215-.055-.409-.162l-5.5-3.035q-.102-.056-.196-.126q-.094-.069-.178-.151t-.156-.173t-.132-.192t-.105-.209q-.045-.107-.076-.22t-.046-.228q-.016-.116-.016-.233V7.283q0-.117.016-.233q.015-.115.046-.228t.076-.22t.105-.209q.06-.1.132-.192t.156-.173q.084-.082.178-.151q.094-.07.196-.126l5.5-3.035q.194-.107.409-.162T10 2.498t.436.056q.215.055.409.162l5.5 3.035q.102.056.196.126q.094.069.178.151t.156.173t.132.192q.059.101.105.209q.045.107.076.22t.046.228t.016.233v3.739");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.urldrljgt {
  d: path("M2.75 6.25L10 10.5l7.25-4.25M10 10.5v8.25m10.75-2.5C20.5 15.5 19.5 15 18 15s-2.75.75-2.75 1.75c0 2.25 5.5 1 5.5 2.75c0 1-1.25 1.5-2.75 1.5s-2.5-.5-2.75-1.25m2.75-6V15m0 6v1m-4 0l8-8");
}

</style>
