<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1-0vf7ft"/><path class="zfgzjccvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:component-create" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n1-0vf7ft {
  d: path("m12.685 19.552l-.95.534q-.168.095-.355.144t-.38.048q-.193 0-.38-.048q-.187-.049-.355-.144l-6.5-3.656q-.087-.049-.166-.108q-.079-.06-.15-.13q-.071-.069-.132-.148t-.112-.164q-.05-.086-.088-.177q-.039-.092-.065-.188t-.039-.194T3 15.123V7.877q0-.099.013-.198q.013-.098.039-.194t.065-.188t.088-.177q.051-.086.112-.164t.132-.148t.15-.13t.166-.108l6.5-3.656q.168-.095.355-.144t.38-.048t.38.048q.187.049.355.144l6.5 3.656q.087.049.166.108q.079.06.15.13q.071.069.132.148t.112.164q.05.086.088.177q.039.092.065.188t.039.194q.013.099.013.198v4.528");
}

.zfgzjccvr {
  d: path("m3 7l8 4.5L19 7m-8 4.5v9m7-5.5v6m-3-3h6");
}

</style>
