<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgf2xtbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:birth-rate" /></template>
<style>
.tgf2xtbjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h13c0 3.5-3 5.5-6.5 5.5s-6.5-2-6.5-5.5m6.5 0V3.5A6.5 6.5 0 0 0 3.5 10m13 0L19 5M4 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.713-1.59q-.262-.2-.573-.305t-.64-.105q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194t-.01.196t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.098 0 .196-.01q.098-.009.194-.028q.097-.02.191-.048q.094-.029.184-.066q.091-.038.178-.084q.086-.046.168-.101t.158-.117t.145-.132t.132-.145t.117-.158t.101-.168q.046-.087.084-.178q.037-.09.066-.184q.028-.094.048-.191q.019-.096.028-.194t.01-.196v-.043M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
