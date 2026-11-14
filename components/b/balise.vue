<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cnd7rabsw"/><path class="kl0lk4qlc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:balise" /></template>
<style>
.cnd7rabsw {
  d: path("M5.5 15h13a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 17.5A2.5 2.5 0 0 1 5.5 15m4-3.5a3.5 3.5 0 0 1 5 0m-7-2a6.5 6.5 0 0 1 9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kl0lk4qlc {
  d: path("M5.25 7.25a9.5 9.5 0 0 1 13.5 0");
}

</style>
