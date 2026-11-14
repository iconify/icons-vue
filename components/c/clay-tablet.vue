<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xsndd2hvk"/><path class="prraqtbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clay-tablet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prraqtbcq {
  d: path("M7.873 7.783za1.047 1.047 0 0 0 1.362.849l2.191-.717a.635.635 0 0 0-.174-1.238l-2.304-.085a1.047 1.047 0 0 0-1.075 1.191m.661 4.704za.998.998 0 0 0 1.343.794l1.467-.558a.641.641 0 0 0-.174-1.238l-1.564-.131a.998.998 0 0 0-1.072 1.133m.661 4.704za1.047 1.047 0 0 0 1.362.849l2.191-.717a.635.635 0 0 0-.174-1.238l-2.304-.086a1.047 1.047 0 0 0-1.075 1.192");
}

.xsndd2hvk {
  d: path("m8.643 3.383l4.209-.591a4.375 4.375 0 0 1 4.941 3.723l1.287 9.16a4.375 4.375 0 0 1-3.723 4.942l-4.209.591a4.375 4.375 0 0 1-4.941-3.723L4.92 8.325a4.375 4.375 0 0 1 3.723-4.942");
}

</style>
