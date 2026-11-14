<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lne1159db"/><path class="n1186pb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:board-card-move" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lne1159db {
  d: path("M3.142 5.48q.121-.171.261-.326q.14-.156.298-.293t.331-.255t.359-.214t.382-.17t.399-.123t.411-.074T6 4h12q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v9q0 .172-.017.343t-.05.34q-.034.168-.084.333t-.115.323q-.066.159-.147.311t-.177.294q-.095.143-.204.276q-.11.133-.231.255q-.122.121-.255.231q-.133.109-.276.204q-.142.096-.294.177t-.311.147t-.323.115t-.333.084q-.169.033-.34.05T18 20H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 16.5v-4.227M8.75 14.3V20m6.5-16v16");
}

.n1186pb3t {
  d: path("M5 15.5h7.5M11 14l1.5 1.5L11 17M6.25 7h3A1.75 1.75 0 0 1 11 8.75v1a1.75 1.75 0 0 1-1.75 1.75h-3A1.75 1.75 0 0 1 4.5 9.75v-1A1.75 1.75 0 0 1 6.25 7");
}

</style>
