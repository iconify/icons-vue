<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q233bwx8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:access-denied-event" /></template>
<style>
.q233bwx8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.057 18H3v-4q.098 0 .196-.01q.098-.009.194-.028q.097-.02.191-.048q.094-.029.184-.066q.091-.038.178-.084q.086-.046.168-.101t.158-.117t.145-.132q.07-.069.132-.145t.117-.158t.101-.168t.084-.178q.037-.09.066-.184q.028-.094.048-.191q.019-.096.028-.194T5 12t-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145q-.069-.07-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T3 10V6h18v4q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T19 12q0 .265.069.521q.069.257.203.486M15.5 15.5l5 5m0-5l-5 5");
}

</style>
