<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="x2nbrrpmx"/><path class="efdiu7bwr"/></g><path class="uaginbcio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bug-edit" /></template>
<style>
.efdiu7bwr {
  d: path("M8.75 6.25a3.25 3.25 0 0 1 6.5 0ZM7.25 14h-3.5m13 0h3.5m-12.5 4.25l-3 1.75m11.5-1.75l3 1.75M8.5 10.75L5.25 9m10.25 1.75L18.75 9M12 12.25v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uaginbcio {
  d: path("m15.25 19.75l.5-2.25l2.5-2.5A1.24 1.24 0 0 1 20 16.75l-2.5 2.5Zm1-2.75L18 18.75");
}

.x2nbrrpmx {
  width: 9.5px;
  height: 12.5px;
  x: 7.25px;
  y: 8.75px;
  rx: 4.75px;
}

</style>
