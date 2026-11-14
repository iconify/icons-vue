<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a22jq4bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:caller-location" /></template>
<style>
.a22jq4bmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.547 17.194C6.983 15.247 2.908 10.124 2.5 4q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T4.5 2H7l1.75 4.5l-2 1.5c1 2.5 3.25 4.75 5.75 5.75l1.5-2l.24.093m4.01 9.657c-2-2-3-3.5-3-5.5a3 3 0 0 1 6 0c0 2-1 3.5-3 5.5");
}

</style>
