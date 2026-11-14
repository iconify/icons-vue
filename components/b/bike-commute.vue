<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jf8g0lbol"/><path class="wbwgk1bjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-commute" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf8g0lbol {
  d: path("M2.5 11.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m18.846 1.099q.154-.539.154-1.099q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37t-.168-.355t-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264q-.152-.125-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T17.5 7.5t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388t-.019.392q0 .557.152 1.093t.445 1.009");
}

.wbwgk1bjo {
  d: path("m6.5 11.5l3-5l2 5Zm3-5h6l-4 5m4-5l2 5m-8-5L9 4.75m-1.25 0h2.75m5 1.75L15 4.75h2m-.75 11.75h3.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-1.5a1.75 1.75 0 0 1 1.75-1.75m.5 0v-2h2.5v2");
}

</style>
