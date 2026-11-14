<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="anmo1f1mh"/><path class="r5_a71ljx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drive-through-lane" /></template>
<style>
.anmo1f1mh {
  d: path("M13.746 12.5H2.5v-3l2-1l2.5-4h6l3 4l.322.129");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r5_a71ljx {
  d: path("M3.5 14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.244-.978q-.065-.116-.144-.222q-.08-.106-.173-.201t-.197-.176q-.105-.082-.219-.149q-.115-.067-.237-.118q-.122-.052-.25-.086q-.128-.035-.26-.052q-.131-.018-.264-.018q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T10 14.5t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.139 0 .276-.019q.138-.019.271-.057q.134-.038.261-.094q.127-.057.245-.13t.225-.162t.2-.191t.172-.217t.141-.239M18.25 11h1.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 18.25 11m.75 5.5v5");
}

</style>
