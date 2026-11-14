<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ox_jlbbkv"/><path class="rtudyx__u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:agent-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ox_jlbbkv {
  d: path("M4.5 10a7 7 0 0 1 14 0m-14 0za2 2 0 0 1 2 2v2a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2");
}

.rtudyx__u {
  d: path("M16.502 14.086L16.5 14v-2q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T18.5 10t.196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v2l-.001.072M18.875 16.5l.024.064a1.44 1.44 0 0 0 1.351.936a.414.414 0 0 1 .293.707l-.192.192a1.5 1.5 0 0 0-.395 1.425L20 20a.38.38 0 0 1-.589.401l-.039-.028a1.5 1.5 0 0 0-1.744 0l-.039.028A.38.38 0 0 1 17 20l.044-.176a1.5 1.5 0 0 0-.395-1.425l-.192-.192a.414.414 0 0 1 .293-.707a1.44 1.44 0 0 0 1.351-.936l.024-.064a.401.401 0 0 1 .75 0");
}

</style>
