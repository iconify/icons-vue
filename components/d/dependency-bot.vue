<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu866-b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dependency-bot" /></template>
<style>
.vu866-b4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.375 10.5h7.25A4.375 4.375 0 0 1 20 14.875v2.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 17.125v-2.25A4.375 4.375 0 0 1 8.375 10.5M12 8v2.5m-.579-8.057za.45.45 0 0 1 .447-.396h.264a.45.45 0 0 1 .447.396a.8.8 0 0 0 .394.596l.239.138a.8.8 0 0 0 .712.043a.45.45 0 0 1 .567.189l.132.229a.45.45 0 0 1-.119.586a.8.8 0 0 0-.319.638v.276a.8.8 0 0 0 .319.638a.45.45 0 0 1 .119.586l-.132.229a.45.45 0 0 1-.567.189a.8.8 0 0 0-.712.043l-.239.138a.8.8 0 0 0-.394.596a.45.45 0 0 1-.447.396h-.264a.45.45 0 0 1-.447-.396a.8.8 0 0 0-.394-.596l-.239-.138a.8.8 0 0 0-.712-.043a.45.45 0 0 1-.567-.189l-.132-.229a.45.45 0 0 1 .119-.586a.8.8 0 0 0 .319-.638v-.276a.8.8 0 0 0-.319-.638a.45.45 0 0 1-.119-.586l.132-.229a.45.45 0 0 1 .567-.189a.8.8 0 0 0 .712-.043l.239-.138a.8.8 0 0 0 .394-.596M9 15.75h.01m5.99 0h.01");
}

</style>
