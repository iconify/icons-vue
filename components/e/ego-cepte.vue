<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qh3qtub8t"/><circle class="hk579qb0n"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ego-cepte" /></template>
<style>
.hk579qb0n {
  cx: 27.865px;
  cy: 28.295px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.qh3qtub8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 18.663h3.059m1.647 4.706H9.5v-9.412h4.706M16.1 31.058h1.941m1.045 2.987H16.1v-5.974h2.986m16.427 2.987h1.942m1.045 2.987h-2.987v-5.974H38.5M26.382 17.132c0-1.765-1.412-3.177-3.177-3.177s-3.176 1.412-3.176 3.177v3.177c0 1.764 1.412 3.059 3.176 3.059s3.177-1.412 3.177-3.06h-3.177m12.118 3.059c-1.765 0-3.059-1.412-3.059-3.059v-3.177c0-1.764 1.412-3.176 3.059-3.176A3.163 3.163 0 0 1 38.5 17.13v3.06a3.163 3.163 0 0 1-3.177 3.176m-21.791 8.593c0 1.12-.896 2.016-2.016 2.016S9.5 33.078 9.5 32.033v-2.016c0-1.12.896-2.016 2.016-1.941c1.12 0 1.941.896 1.941 1.941m8.527 4.028V28.07h1.942c1.12 0 2.016.896 2.016 2.016s-.896 2.016-2.016 2.016h-1.942m7.788-4.031h3.883m-1.941 5.974v-5.974m-3.965 1.494c.373-.15.373-.523.373-.747v-.523");
}

</style>
