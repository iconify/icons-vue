<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gyx0vibeg"/><path class="lrght0wnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:epic-at-risk" /></template>
<style>
.gyx0vibeg {
  d: path("M11.3 20H2.5V9h14.6");
}

.lrght0wnk {
  d: path("M6.5 9V5.5q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145q.069-.07.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T8.5 3.5h11q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v4q0 .092-.009.184t-.025.183q-.017.091-.042.18q-.025.088-.059.175q-.033.086-.074.168t-.09.162q-.048.078-.104.152t-.118.142t-.13.131q-.068.062-.142.118t-.152.104q-.078.049-.161.09q-.082.041-.169.075q-.086.033-.174.059q-.089.025-.18.042t-.183.026M17.75 13.75l4 7.5h-8Zm0 3V18m0 1.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
