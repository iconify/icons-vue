<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9trymbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-tractor" /></template>
<style>
.m9trymbgh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.5 9l-1-6h-6v6h11a1.5 1.5 0 0 1 1.5 1.5v3M2 16.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm12.87 1.077q-.139-.192-.32-.346q-.18-.155-.391-.262t-.441-.164q-.231-.055-.468-.055q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194t-.01.196q0 .169.028.335q.029.167.084.326t.138.307t.187.28q.105.132.231.244q.126.113.269.202t.3.155q.156.064.32.101M20.5 14L18 17.75h3.5L19 21.5");
}

</style>
