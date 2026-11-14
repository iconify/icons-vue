<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4c3g-b3c"/><path class="ky3p5-b-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:driver-rest-stop" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ky3p5-b-g {
  d: path("M3.5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.344-.774q-.057-.135-.133-.261t-.169-.239t-.203-.212t-.232-.179q-.122-.082-.255-.144q-.133-.063-.274-.106q-.14-.042-.286-.064T12 14q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T10 16t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T12 18q.132 0 .262-.017q.131-.018.258-.052t.249-.085q.121-.05.235-.116t.218-.147q.104-.08.197-.174t.173-.198q.079-.105.145-.219M13.25 7v3.5h6.25m-3 5.5v5.5m0-2.25h5.25v2.25M20 16.75h.5A1.25 1.25 0 0 1 21.75 18a1.25 1.25 0 0 1-1.25 1.25H20A1.25 1.25 0 0 1 18.75 18A1.25 1.25 0 0 1 20 16.75");
}

.u4c3g-b3c {
  d: path("M14.601 14H2.5V3h9v4H15l4.5 3.5V14h-1.099");
}

</style>
