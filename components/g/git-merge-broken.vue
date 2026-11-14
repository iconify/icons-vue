<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="poa4r25xv"/><path class="wddphhbzi"/><path class="ru1ymkblj"/><path class="nubt4fb4o"/><path class="dc5op7b-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-merge-broken" /></template>
<style>
.dc5op7b-p {
  d: path("M9.62012 17.2053C11.3707 18.3567 13.5424 19 16 19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nubt4fb4o {
  d: path("M5 8C5 10.7804 5.8234 13.1948 7.2744 15.0476");
}

.poa4r25xv {
  d: path("M8 5C8 6.6569 6.6569 8 5 8C3.3431 8 2 6.6569 2 5C2 3.3431 3.3431 2 5 2C6.6569 2 8 3.3431 8 5Z");
}

.ru1ymkblj {
  d: path("M5 8V22");
}

.wddphhbzi {
  d: path("M22 19C22 20.6569 20.6569 22 19 22C17.3431 22 16 20.6569 16 19C16 17.3431 17.3431 16 19 16C20.6569 16 22 17.3431 22 19Z");
}

</style>
