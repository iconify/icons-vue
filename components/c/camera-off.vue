<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hiou08brm"/><path class="jo8acdblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-off" /></template>
<style>
.hiou08brm {
  d: path("M16.016 20H5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132t-.132-.145t-.117-.158t-.101-.168q-.046-.087-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T3 18V8.5q0-.303.09-.593q.09-.289.261-.539m5.266-2.73L9 4h6l1.5 2.5H19q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T21 8.5v8.512");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo8acdblk {
  d: path("M8.321 12.275q-.071.359-.071.725q0 .184.018.368q.018.183.054.364q.036.18.089.357q.054.176.124.346t.158.333t.189.315q.102.154.219.296t.247.273t.273.247t.296.219t.315.189q.163.087.333.158q.17.07.346.124q.177.053.357.089q.181.036.364.054q.184.018.368.018q.365 0 .723-.07m2.73-5.142q-.141-.333-.343-.633t-.458-.556t-.556-.458t-.633-.344M3.5 3.5l17 17");
}

</style>
