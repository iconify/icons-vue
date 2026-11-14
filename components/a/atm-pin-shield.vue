<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u59qre7gh"/><path class="u4u22kbek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atm-pin-shield" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u4u22kbek {
  d: path("M21.5 3h-8C9 3 6 6 5.25 10.25c-.25 1 1 1.5 1.75.75c1.25-1.5 3-2.75 5.5-2.75h2l2 3c.5.75 1.5.5 1.5-.25l-.5-2.75h4m-11.25-2.5l2.25-.5");
}

.u59qre7gh {
  d: path("M12.817 11.008q.183.112.352.245m1.181 1.732q.15.496.15 1.015v4q0 .172-.017.343t-.05.34q-.034.168-.084.333t-.115.323t-.147.311t-.177.294q-.095.143-.204.276q-.11.133-.231.255q-.122.121-.255.231q-.133.109-.276.204q-.142.096-.294.177t-.311.147t-.323.115t-.333.084q-.169.033-.34.05T11 21.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 18v-4q0-.407.093-.803q.094-.396.276-.76M8.5 13.75h.01m2.99 0h.01M5.5 16.5h.01m2.99 0h.01m2.99 0h.01M5.5 19.25h.01m2.99 0h.01m2.99 0h.01");
}

</style>
