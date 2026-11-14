<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n4qp-uoia"/><path class="v38rxrm3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:energy-drink" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4qp-uoia {
  d: path("M8 2.5h8L17.5 5v14.5a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2V5Z");
}

.v38rxrm3u {
  d: path("m11.798 9.717l-1.509 2.157A.716.716 0 0 0 10.875 13a1.098 1.098 0 0 1 1.07 1.341l-.32 1.409a.384.384 0 0 0 .712.267l1.511-2.806A.82.82 0 0 0 13.125 12a1.01 1.01 0 0 1-.965-1.312l.215-.688a.325.325 0 0 0-.577-.283");
}

</style>
