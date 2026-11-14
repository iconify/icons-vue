<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t3eoqbcex"/><path class="v_804tj3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:achievement-progress" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t3eoqbcex {
  d: path("M3 12a9 9 0 1 1 11.781 8.56");
}

.v_804tj3f {
  d: path("m12.5 9.25l.159.396a1.5 1.5 0 0 0 1.257.937l.511.047a.569.569 0 0 1 .323.995l-.36.315a1.5 1.5 0 0 0-.488 1.397l.118.647a.609.609 0 0 1-.895.641l-.397-.22a1.5 1.5 0 0 0-1.456 0l-.397.22a.609.609 0 0 1-.895-.641l.118-.647a1.5 1.5 0 0 0-.488-1.397l-.36-.315a.569.569 0 0 1 .323-.995l.511-.047a1.5 1.5 0 0 0 1.257-.937l.159-.396a.539.539 0 0 1 1 0");
}

</style>
