<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r-66kdr5g"/><path class="zz8_50xgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:container-health" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r-66kdr5g {
  d: path("m12.249 19.297l-.514.289q-.168.095-.355.144t-.38.048q-.193 0-.38-.048q-.187-.049-.355-.144l-6.5-3.656q-.087-.049-.166-.108q-.079-.06-.15-.13q-.071-.069-.132-.148t-.112-.164q-.05-.086-.088-.177q-.039-.092-.065-.188t-.039-.194T3 14.623V7.877q0-.099.013-.198q.013-.098.039-.194t.065-.188t.088-.177q.051-.086.112-.164t.132-.148t.15-.13t.166-.108l6.5-3.656q.168-.095.355-.144t.38-.048t.38.048q.187.049.355.144l6.5 3.656q.087.049.166.108q.079.06.15.13q.071.069.132.148t.112.164q.05.086.088.177q.039.092.065.188t.039.194q.013.099.013.198v4.828");
}

.zz8_50xgn {
  d: path("m3 7l8 4.5L19 7m-8 4.5V20m7 1.5l-3-3a1.75 1.75 0 0 1 3-2.25a1.75 1.75 0 0 1 3 2.25Z");
}

</style>
