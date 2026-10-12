<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq3nwmb1a"/><path class="yom17qb7y"/><rect class="dbob7m8ob"/><path class="l6w797b9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chain-padlock" /></template>
<style>
.dbob7m8ob {
  width: 7.5px;
  height: 8px;
  x: 12.75px;
  y: 13.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6w797b9j {
  d: path("M16.5 16.25V18");
}

.oq3nwmb1a {
  d: path("m8.9 5.16l.89.89a1.25 1.25 0 0 0 1.76-1.76l-.89-.89A1.25 1.25 0 0 0 8.9 5.16m2.65.89l.71.71m0 1.76l.89.89a1.25 1.25 0 0 0 1.76-1.76l-.89-.89a1.25 1.25 0 0 0-1.76 1.76");
}

.yom17qb7y {
  d: path("M14.25 13.25V11a2.25 2.25 0 0 1 4.5 0v2.25");
}

</style>
