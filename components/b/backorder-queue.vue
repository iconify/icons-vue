<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vze8ulbhf"/><path class="gistmebfi"/><path class="j_dy58bdg"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backorder-queue" /></template>
<style>
.gistmebfi {
  d: path("M12.75 14.854V19.5q0 .098-.01.196q-.009.098-.028.194q-.02.097-.048.191q-.029.094-.066.184q-.038.091-.084.178q-.046.086-.101.168t-.117.158t-.132.145t-.145.132t-.158.117t-.168.101q-.087.046-.178.084q-.09.037-.184.066q-.094.028-.191.048q-.096.019-.194.028t-.196.01H5.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T3.5 19.5v-11q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145q.069-.07.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T5.5 6.5h4l3.25 3.25v4.904");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_dy58bdg {
  d: path("M9.5 6.5v3.25h3.25M6.25 14H10m-3.75 3.5H8.5m7-2.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.vze8ulbhf {
  d: path("M8 6.5v-2a2 2 0 0 1 2-2h5.5l4 4v5.25");
}

</style>
