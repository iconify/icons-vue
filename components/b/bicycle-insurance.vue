<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l5-iscb_t"/><path class="raskcp2lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bicycle-insurance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5-iscb_t {
  d: path("M2.5 11.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m18.713 1.487q.287-.716.287-1.487q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37t-.168-.355t-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264q-.152-.125-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T17.5 7.5t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388t-.019.392q0 .557.152 1.093t.445 1.009");
}

.raskcp2lm {
  d: path("m6.5 11.5l3-5.5H15M9.5 6l2 5.5h-5M15 6l-3.5 5.5M15 6l2.5 5.5M15 6l-.75-2.5h2.25m2 11.5l3 1v2.5c0 1.75-1.5 2.75-3 3.25c-1.5-.5-3-1.5-3-3.25V16Z");
}

</style>
