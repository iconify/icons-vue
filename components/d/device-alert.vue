<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="urohclmyx"/><path class="txa8_ob4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:device-alert" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.txa8_ob4f {
  d: path("M5.125 9h1.25A2.625 2.625 0 0 1 9 11.625v7.25A2.625 2.625 0 0 1 6.375 21.5h-1.25A2.625 2.625 0 0 1 2.5 18.875v-7.25A2.625 2.625 0 0 1 5.125 9M18 14.5V18m0 3h.01");
}

.urohclmyx {
  d: path("M6 9V5q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T8 3h11.5q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T21.5 5v9q0 .216-.046.427t-.136.408q-.091.196-.221.368q-.13.173-.293.314M15.185 16H9");
}

</style>
