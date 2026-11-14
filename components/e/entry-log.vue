<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ky_v755kz"/><path class="mu1hqhbvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:entry-log" /></template>
<style>
.ky_v755kz {
  d: path("M7 4H5.5q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132q-.07.069-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T3.5 6v13.5q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01h8.343m2.657-9.815V6q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145q-.069-.07-.145-.132t-.158-.117t-.168-.101t-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T14.5 4H13");
}

.mu1hqhbvu {
  d: path("M7 2.5h6V6H7ZM6.5 10h7m-7 4H11m7.5.5H21v7h-2.5m-5-3.5h4.75m-2-2l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
