<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ld4jugx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:encapsulation" /></template>
<style>
.l_ld4jugx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.955 15.701l-.809.809q-.139.139-.291.264q-.152.124-.315.233t-.337.202t-.355.168t-.369.132t-.381.095q-.192.039-.388.058t-.392.019t-.392-.019t-.388-.058t-.381-.095q-.188-.057-.369-.132q-.182-.075-.355-.168q-.174-.093-.337-.202t-.315-.233t-.291-.264t-.264-.291q-.124-.152-.233-.315t-.202-.337t-.168-.355t-.132-.369t-.095-.381t-.058-.388t-.019-.392t.019-.392t.058-.388q.038-.193.095-.381t.132-.369t.168-.355t.202-.337t.233-.315t.264-.291l6.364-6.364q.139-.139.291-.264q.152-.124.315-.233t.337-.202t.355-.168t.369-.132t.381-.095t.388-.058t.392-.019t.392.019t.388.058q.193.038.381.095t.369.132q.182.075.355.168q.174.093.337.202t.315.233t.291.264t.264.291t.233.315t.202.337t.168.355t.132.369t.095.381q.039.192.058.388t.019.392t-.019.392t-.058.388t-.095.381t-.132.369q-.075.182-.168.355q-.093.174-.202.337t-.233.315t-.264.291l-.959.959M7.75 7.75l4.596 4.596m5.404.904l4 1.5v3c0 2.25-2 3.5-4 4.25c-2-.75-4-2-4-4.25v-3Z");
}

</style>
