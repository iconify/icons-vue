<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="uwhljpbkf"/></g><path class="notrppkqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:book-minus" /></template>
<style>
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

.notrppkqh {
  d: path("M14.75 17.5h5.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uwhljpbkf {
  d: path("M4.75 18.75V5.25a2.5 2.5 0 0 1 2.5-2.5h10a2 2 0 0 1 2 2v11.5H6.75a2 2 0 0 0-2 2Zm0 0a2.5 2.5 0 0 0 2.5 2.5h12v-4.5m-10-9.5h5.5");
}

</style>
