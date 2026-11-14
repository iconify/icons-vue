<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yx8x-lflh"/><path class="iitx6hd3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:automation-edit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iitx6hd3b {
  d: path("M7.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m8.25 10.375v-.504a1.5 1.5 0 0 1 .439-1.06l2.5-2.5a1.5 1.5 0 0 1 2.122 0l.128.128a1.5 1.5 0 0 1 0 2.122l-2.5 2.5a1.5 1.5 0 0 1-1.06.439h-.504a1.125 1.125 0 0 1-1.125-1.125");
}

.yx8x-lflh {
  d: path("m8.071 4.044l.054-.544a1.39 1.39 0 0 1 1.381-1.25h.988a1.39 1.39 0 0 1 1.381 1.25l.054.544a1.5 1.5 0 0 0 .661 1.099l.253.169a1.5 1.5 0 0 0 1.39.145l.531-.212a1.5 1.5 0 0 1 1.874.674l.263.484A1.445 1.445 0 0 1 16.5 8.25l-.4.3a1.5 1.5 0 0 0-.6 1.2v.5a1.5 1.5 0 0 0 .6 1.2l.4.3a1.445 1.445 0 0 1 .401 1.847l-.263.484a1.5 1.5 0 0 1-1.874.674l-.531-.212a1.5 1.5 0 0 0-1.39.145l-.253.169a1.5 1.5 0 0 0-.661 1.099l-.054.544a1.39 1.39 0 0 1-1.381 1.25h-.988a1.39 1.39 0 0 1-1.381-1.25l-.054-.544a1.5 1.5 0 0 0-.661-1.099l-.253-.169a1.5 1.5 0 0 0-1.39-.145l-.531.212a1.5 1.5 0 0 1-1.874-.674l-.263-.484A1.445 1.445 0 0 1 3.5 11.75l.4-.3a1.5 1.5 0 0 0 .6-1.2v-.5a1.5 1.5 0 0 0-.6-1.2l-.4-.3a1.445 1.445 0 0 1-.401-1.847l.263-.484a1.5 1.5 0 0 1 1.874-.674l.531.212a1.5 1.5 0 0 0 1.39-.145l.253-.169a1.5 1.5 0 0 0 .661-1.099");
}

</style>
