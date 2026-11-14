<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yx8x-lflh"/><path class="qr0x4tbca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:automation-action" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qr0x4tbca {
  d: path("M7.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m8.25 8.5h6M19 16l2.5 2.5L19 21");
}

.yx8x-lflh {
  d: path("m8.071 4.044l.054-.544a1.39 1.39 0 0 1 1.381-1.25h.988a1.39 1.39 0 0 1 1.381 1.25l.054.544a1.5 1.5 0 0 0 .661 1.099l.253.169a1.5 1.5 0 0 0 1.39.145l.531-.212a1.5 1.5 0 0 1 1.874.674l.263.484A1.445 1.445 0 0 1 16.5 8.25l-.4.3a1.5 1.5 0 0 0-.6 1.2v.5a1.5 1.5 0 0 0 .6 1.2l.4.3a1.445 1.445 0 0 1 .401 1.847l-.263.484a1.5 1.5 0 0 1-1.874.674l-.531-.212a1.5 1.5 0 0 0-1.39.145l-.253.169a1.5 1.5 0 0 0-.661 1.099l-.054.544a1.39 1.39 0 0 1-1.381 1.25h-.988a1.39 1.39 0 0 1-1.381-1.25l-.054-.544a1.5 1.5 0 0 0-.661-1.099l-.253-.169a1.5 1.5 0 0 0-1.39-.145l-.531.212a1.5 1.5 0 0 1-1.874-.674l-.263-.484A1.445 1.445 0 0 1 3.5 11.75l.4-.3a1.5 1.5 0 0 0 .6-1.2v-.5a1.5 1.5 0 0 0-.6-1.2l-.4-.3a1.445 1.445 0 0 1-.401-1.847l.263-.484a1.5 1.5 0 0 1 1.874-.674l.531.212a1.5 1.5 0 0 0 1.39-.145l.253-.169a1.5 1.5 0 0 0 .661-1.099");
}

</style>
