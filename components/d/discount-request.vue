<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qhlyvlljr"/><path class="d70ss5t6t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:discount-request" /></template>
<style>
.d70ss5t6t {
  d: path("M15.75 14.75h4.75a1 1 0 0 1 1 1V19a1 1 0 0 1-1 1h-3.25l-2.5 1.75v-6a1 1 0 0 1 1-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qhlyvlljr {
  d: path("M11.971 19.913q-.225.065-.456.099q-.231.035-.464.038q-.234.003-.466-.024q-.232-.028-.458-.086q-.227-.059-.443-.147q-.217-.087-.419-.203q-.203-.116-.389-.258t-.351-.307l-3.55-3.55q-.122-.122-.231-.255q-.109-.132-.204-.275q-.096-.143-.177-.295t-.147-.311q-.066-.158-.116-.323q-.049-.164-.083-.333t-.05-.34T3.95 13t.017-.343q.016-.171.05-.34t.083-.333t.116-.323t.147-.311t.177-.295t.204-.275q.109-.133.231-.255l7-7q.244-.244.53-.435q.287-.192.606-.324q.318-.132.656-.199t.683-.067H18q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T21.5 6v3.55q0 .34-.065.674q-.066.334-.194.649q-.129.315-.316.599q-.186.284-.424.527M9.5 13.5l4-4M10 10h.01");
}

</style>
