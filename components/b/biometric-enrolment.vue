<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v07ttbc5j"/><path class="pw5fnnbqm"/><path class="x0ujjn6uc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:biometric-enrolment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pw5fnnbqm {
  d: path("M8 14.5q-.114-.178-.212-.366t-.179-.384t-.144-.399t-.108-.409t-.071-.418q-.026-.21-.033-.422t.004-.423t.042-.422q.03-.209.079-.416q.049-.206.116-.407q.068-.201.152-.395q.085-.195.187-.38q.102-.186.219-.363q.118-.176.251-.341q.134-.165.281-.317t.307-.291t.333-.263t.354-.232t.373-.199t.39-.166q.199-.074.403-.13t.413-.093q.209-.038.42-.057T12 7.188t.423.019t.42.057q.208.037.413.093q.204.056.403.13q.198.074.39.166q.191.091.373.199t.354.232t.333.263q.221.191.417.408q.196.218.364.457t.305.498t.242.532q.104.273.174.557t.105.574t.034.583t-.038.583");
}

.v07ttbc5j {
  d: path("M2.5 7.5V5A2.5 2.5 0 0 1 5 2.5h2.5m9 0H19A2.5 2.5 0 0 1 21.5 5v2.5m-19 9V19A2.5 2.5 0 0 0 5 21.5h2.5m2.75-8.5a2 2 0 1 1 3.5 0");
}

.x0ujjn6uc {
  d: path("M5 14.5A7.5 7.5 0 1 1 19.5 12M18 15v6m-3-3h6");
}

</style>
