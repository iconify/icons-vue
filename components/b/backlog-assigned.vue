<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="alhsm-bnd"/><path class="lc88f6b1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backlog-assigned" /></template>
<style>
.alhsm-bnd {
  d: path("M13.657 16.5H2.5v-3q.098 0 .196-.01q.098-.009.194-.028q.097-.02.191-.048q.094-.029.184-.066q.091-.038.178-.084q.086-.046.168-.101t.158-.117t.145-.132t.132-.145t.117-.158t.101-.168q.046-.087.084-.178q.037-.09.066-.184q.028-.094.048-.191q.019-.096.028-.194t.01-.196t-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T2.5 9.5v-3h14v3q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194t-.01.196q0 .361.126.699");
}

.lc88f6b1r {
  d: path("M5.5 3.5H18A1.5 1.5 0 0 1 19.5 5v5m-5 11.25c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5Zm1.75-6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
