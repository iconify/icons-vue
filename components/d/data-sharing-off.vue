<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4guadbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-sharing-off" /></template>
<style>
.n4guadbor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M5.602 9.532q-.109.017-.216.044q-.107.028-.211.064t-.204.082q-.101.045-.197.099t-.187.117q-.091.062-.176.132t-.164.148t-.15.161t-.136.174q-.063.09-.119.185t-.103.195t-.085.203t-.067.21t-.048.215q-.02.109-.029.219T3.5 12q0 .123.012.245t.036.243q.024.12.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06q.121.024.243.036T6 14.5q.109 0 .218-.01q.109-.009.217-.028q.107-.019.213-.047q.105-.029.208-.066q.102-.037.201-.084q.099-.046.194-.101q.095-.054.184-.117q.09-.063.173-.133q.084-.07.161-.148t.147-.161t.133-.173t.117-.184t.101-.194t.083-.202t.066-.208t.047-.213m7.368 7.314q.162.282.39.513t.508.396M12.485 8.491L15.75 6.75m-7.5 6.5l2.294 1.224M3.5 3.5l17 17");
}

</style>
