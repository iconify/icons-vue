<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiebu6bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:armadillo" /></template>
<style>
.iiebu6bgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 13.5l4-3v-3l1.75 2C10 8 12 7.25 14 7.25c3.5 0 5.5 2.5 5.5 5.75l1.5 3.5l-2-2H7.5Zm6.5 1v3m6-3v3M11 8v6.5m3-7.25v7.25M17 8v6.5");
}

</style>
