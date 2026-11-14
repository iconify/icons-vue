<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="etzue2bmp"/><path class="rfw-t--vp"/><path class="qr_qq3bht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:email-replied" /></template>
<style>
.etzue2bmp {
  d: path("M16.528 11.5H14l-3 5v.5H4.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132t-.132-.145t-.117-.158t-.101-.168q-.046-.087-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T2.5 15V6q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145q.069-.07.145-.132t.158-.117t.168-.101t.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T4.5 4h13q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194T19.5 6v5.5h-2.072");
}

.qr_qq3bht {
  d: path("m17 15l-1.75 1.75L17 18.5");
}

.rfw-t--vp {
  d: path("m6 7.5l5 3.5l5-3.5m5 13.25v-1.5a2.5 2.5 0 0 0-2.5-2.5h-3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
