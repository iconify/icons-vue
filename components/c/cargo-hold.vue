<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0g9qtbga"/><rect class="ain8fk9xd"/><rect class="okzjf3bbo"/><path class="mqgf1eb4c"/><rect class="uhcln7btt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cargo-hold" /></template>
<style>
.ain8fk9xd {
  width: 4px;
  height: 4px;
  x: 6.75px;
  y: 13.5px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqgf1eb4c {
  d: path("M12 2.75V5.5");
}

.okzjf3bbo {
  width: 4px;
  height: 4px;
  x: 13.25px;
  y: 13.5px;
  rx: 0.75px;
}

.r0g9qtbga {
  d: path("M2.75 9h4.5m9.5 0h4.5M2.75 9l1.9 10.5a2 2 0 0 0 2 1.75h10.7a2 2 0 0 0 2-1.75L21.25 9");
}

.uhcln7btt {
  width: 4.5px;
  height: 4.5px;
  x: 9.75px;
  y: 5.5px;
  rx: 0.75px;
}

</style>
