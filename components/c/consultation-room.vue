<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_j98bcif"/><path class="m2n9oobwf"/><path class="tg_yatbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consultation-room" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2n9oobwf {
  d: path("M4.5 17v4.5m15-4.5v4.5M4.552 9.441q.191.192.417.343t.476.256q.251.104.517.157t.538.053q.161 0 .321-.019t.317-.056q.157-.038.308-.093q.152-.055.296-.128t.278-.162t.257-.193q.123-.105.233-.223q.11-.117.206-.247m-.848-4.014q-.182-.105-.379-.181m-1.923-.021q-.197.072-.381.172M2.5 15c0-2.25 1.75-3.75 4-3.75s4 1.5 4 3.75m4.25-7.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M13.5 15c0-2.25 1.75-3.75 4-3.75s4 1.5 4 3.75");
}

.p_j98bcif {
  fill: currentColor;
  d: path("M3.5 15h17a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1a1 1 0 0 1 1-1");
}

.tg_yatbzl {
  fill: currentColor;
  d: path("M5.25 5.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
