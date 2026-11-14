<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a60p8t9gl"/><path class="ftejrpbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charger-public" /></template>
<style>
.a60p8t9gl {
  d: path("M7.5 2.5h3A3.5 3.5 0 0 1 14 6v12a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 4 18V6a3.5 3.5 0 0 1 3.5-3.5M14 8h2a2.5 2.5 0 0 1 2.5 2.5V15m-.25 0h.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 18.25 15");
}

.ftejrpbvp {
  d: path("M8.75 5.5h.5A1.75 1.75 0 0 1 11 7.25v.5A1.75 1.75 0 0 1 9.25 9.5h-.5A1.75 1.75 0 0 1 7 7.75v-.5A1.75 1.75 0 0 1 8.75 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
